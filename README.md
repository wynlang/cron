# cron — Official Wyn Package

Schedule recurring tasks. Pure Wyn.

## Install

```bash
wyn pkg install github.com/wynlang/cron
```

## Usage

```wyn
// Run every 60 seconds
var interval = 60
while true {
    do_work()
    System.sleep(interval * 1000)
}
```
