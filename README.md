# go-get-test

Playing around with "go get". All dependency libraries must be public, sad but true.

## Prerequisites
* Go v1.10
* The `~/go/` directory is assumed as the value of `$GOPATH`, see [https://golang.org/doc/code.html](https://golang.org/doc/code.html)

## Build

Make sure that your system has met the prerequisites above before running the following build steps.

### 1. Clone The Repository

Clone the repository inside `~/go/src/bitbucket.org/qosdil/`, so it will create `~/go/src/bitbucket.org/qosdil/go-get-test`.

### 2. Install Dependencies and Build

Move into the cloned repository, then run the following:

	$ go get
	
## Run

After running the steps above, you can run the service:

	$ ~/go/bin/go-get-test

&copy; 2018 [qosdil@gmail.com](mailto://qosdil@gmail.com)