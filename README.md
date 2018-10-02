# libjpeg-turbo-exports
prebuilt binaries for libjpeg-turbo v1.4.1

## Install
`cp -rf linux-x64/* /usr/local/`

## Usage
djpeg -bmp test0.jpg > test1.bmp
cjpeg -quality 80 -progressive test1.bmp > test1b.jpg

