# bserv
HTTP server in bash. For now only plaintext files are supported. Can serve GET requests

## Usage
Launch bserv on the first run and it will generate default config file (`config.sh`) and default resource not found file (`404.html`). Configuration can then be costumised. Standard way to launch bserv is through the launcher script (`launch`)

### launch
Options:
- `-r web_dir` - changes the root directory for the server
- `-p port` - changes the listening port for server
- `-h` - displays usage information

### serv
Options:
- `-r web_dir` - changes the root directory for the parser
- `-h` - displays usage information
