# flukes
Tool for docker-compose style docker log tailing..


        usage: flukes [-h] [-t TAIL] [containers [containers ...]]

        positional arguments:
          containers            Containers to tail logs from. Defaults to all running
                                containers.

        optional arguments:
          -h, --help            show this help message and exit
          -t TAIL, --tail TAIL  Number of lines to tail (passed to 'docker logs')
