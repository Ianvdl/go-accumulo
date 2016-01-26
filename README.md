# go-accumulo
Thrift generated Golang bindings for Apache Accumulo

##Downloading

`go get github.com/Ianvdl/go-accumulo/proxy`

##Notes

This code is the exact output from `thrift -r --gen go proxy.thrift`, apart from multiple `[]byte` <-> `string` type mismatch errors that were fixed after code generation. The proxy.thrift file from accumulo 1.7.0 was used.
