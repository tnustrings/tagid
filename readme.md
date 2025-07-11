# lily

languages word by word in go

```
$ echo "Dzień dobry" | lily pl
Dzień [[day]] dobry [[good]]
```

## install and try

**on linux with apt**

download the [lily-\<version\>.deb](https://github.com/tnustrings/lily/releases), then say

```
sudo apt install ./lily-<version>.deb
```

**on any os with go**

```
go install github.com/tnustrings/lily
```

**try**

try feeding it some text:

```
echo "Dzień dobry" | lily pl
```

there's also a lily [browser
extension](https://chromewebstore.google.com/detail/tagid-with-google-dict/aacfmkdpcdadjcpohbjfcddomedmfdai).

## code

the code is written in codetext, install from
[here](https://github.com/tnustrings/codetext).

then say:

```
ct lily.ct
```

to generate the go code.