# Go Error Handling Sample

To run sample:

```sh
> go run sample1/main.go

open /Users/caichengyang/.settings.xml: no such file or directory
exit status 1
```

```sh
> go run sample2/main.go

could not read config: open failed: open /Users/caichengyang/.settings.xml: no such file or directory
exit status 1
```

```sh
> go run sample3/main.go

could not read config: open failed: open /Users/caichengyang/.settings.xml: no such file or directory
exit status 1
```

```sh
> go run sample4/main.go

open /Users/caichengyang/.settings.xml: no such file or directory
open failed
main.ReadFile
        /Users/caichengyang/go/src/github.com/ethancai/goErrorHandlingSample/sample4/main.go:15
main.ReadConfig
        /Users/caichengyang/go/src/github.com/ethancai/goErrorHandlingSample/sample4/main.go:27
main.main
        /Users/caichengyang/go/src/github.com/ethancai/goErrorHandlingSample/sample4/main.go:32
runtime.main
        /usr/local/Cellar/go/1.9.2/libexec/src/runtime/proc.go:195
runtime.goexit
        /usr/local/Cellar/go/1.9.2/libexec/src/runtime/asm_amd64.s:2337
could not read config
main.ReadConfig
        /Users/caichengyang/go/src/github.com/ethancai/goErrorHandlingSample/sample4/main.go:28
main.main
        /Users/caichengyang/go/src/github.com/ethancai/goErrorHandlingSample/sample4/main.go:32
runtime.main
        /usr/local/Cellar/go/1.9.2/libexec/src/runtime/proc.go:195
runtime.goexit
        /usr/local/Cellar/go/1.9.2/libexec/src/runtime/asm_amd64.s:2337
exit status 1

```