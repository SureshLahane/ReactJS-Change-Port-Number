# ReactJS-Change-Port-Number
How to specify a port to run a create-react-app based project?

If you don't want to set the environment variable, another option is to modify the scripts part of package.json from:

### "start": "react-scripts start"

to

## Linux (tested on Ubuntu 14.04/16.04) and MacOS (tested by @aswin-s on MacOS Sierra 10.12.4):

### "start": "PORT=3006 react-scripts start"

or (may be) more general solution by @IsaacPak

### "start": "export PORT=3006 react-scripts start"

Windows @JacobEnsor solution

### "start": "set PORT=3006 && react-scripts start"


