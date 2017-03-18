# swank.ros

Small Roswell script for starting a swank server.

## Usage

```
$ swank
;; Swank started at port: 4005.

$ swank --port 4008
;; Swank started at port: 4008.

$ swank --interface 0.0.0.0 ;; invoke swank to be connected from other hosts.
;; Swank started at port: 4005.
```

In Emacs, you can connect to the REPL with `M-x slime-connect<RET>localhost<RET>4005`.

## Installation

```
$ ros install fukamachi/swank-ros
```
