## argument parser
```Python
import sys
import argparse

def parse_arguments(argv):
    parser = argparse.ArgumentParser()
    parser.add_argument('necessary', type=str,
                        help='necessary argument')
    parser.add_argument('--optional', type=str,
                        help='Option argumnent')
    return parser.parse_args(argv)


if __name__ == '__main__':
    main(parse_arguments(sys.argv[1:]))
```
