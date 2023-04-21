Display carriage return and other special characters in Unix or Linux

`od -c filename`
`od -c myfile.txt`

Cat version of the same command:

`cat -v filename`

Tools we can use to convert from unix to dos:

`unix2dos myfile.txt`
`unix2dos -b myfile.txt`

Convert from DOS to unix:

`dos2unix myfile.txt`
Create new file instead of overwriting original:
`dos2unix -n input.txt output.txt`
