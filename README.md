# go_project

## Project to list environment variables
* os.Environ to list all key/values of the environment
* os.Environ() returns a slice of strings in the form KEY=value
* used strings.Split to get the key and value
* print all the keys and values

## Technologies
Project is created with: Go lang
* go1.17.6 linux/amd64
* Os: CentOS Linux release 8.5.2111

## Setup
To run this project, install go locally using rpm:
* $ download the Go language from https://golang.org/dl/
* $ create a dir using mkdir go_project
* $ cd go_project
* $ download the package to go_project
* $ tar the file tar go1.15.6.linux-amd64.tar.gz -C /usr/local -xzf 
* $ Open up your .bashrc or .bash_profile file and add the following lines
  export PATH=$PATH:/usr/local/go/bin
  export GOPATH="/mnt/c/Users/${user}/directory/to/your/golang/workspace"
* $ save the file and run the source file
  source ~/.bash_profile
* $ check the Go version
  go version

## How to run the project
*  go run hello.go 
