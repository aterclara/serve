# serve

Acts as a wrapper around the SimpleHTTPServer module

Serves files from a given directory on a given port

## Install
Add to a bin directory found in the PATH envar e.g. ~/.local/bin

Make it executable
```bash
chmod +x serve
```

## Usage
```bash
serve <dir> <port>
serve /tmp/html 1234         # serving /tmp/html on port 8088
serve /tmp/html              # serving /tmp/html on port 1024
serve                        # serving cwd       on port 8088
```

