# Configure

## Additional Drivers

[this video](https://www.youtube.com/watch?v=fHh5yrERvHw&list=PLAyUwmL7et7O8NsNz_7Tn8K8SKgbc0BP6&index=10)

### Choose the correct graphics driver

## Install Nerd Fonts

[github.com](https://github.com/ryanoasis/nerd-fonts/)
[youtube.com](https://www.youtube.com/watch?v=cBOaYidGaCQ)

## Sync Dotfiles

Dotfiles are...

[dotfiles](https://github.com/hfridholm/dotfiles)

Make utillities accessable from anywhere:
`.bashrc`
```bash
...

UTILS_DIR=/home/hampus/Documents/Programming

export PATH=$PATH\
:$UTILS_DIR/hashing/binary\
:$UTILS_DIR/passman/binary\
:$UTILS_DIR/crypto/binary\
:$UTILS_DIR/procom/binary
```