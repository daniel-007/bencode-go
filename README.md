bencode-go
==========

A Go language binding for encodeing and decoding data in the bencode format that is used by the BitTorrent peer-to-peer file sharing protocol.

Quick Start
-----------

Get the package

    go get -u github.com/jackpal/bencode-go

Import the package
------------------

    import bencode "github.com/jackpal/bencode-go"

Decode a bencode stream
-----------------------

   data, err := bencode.Decode(reader)

Encode an object into a bencode stream
--------------------------------------

   err := bencode.Marshal(writer, data)

Complete documentation
----------------------

http://go.pkgdoc.org/github.com/jackpal/bencode-go

License
-------

This project is licensed under the Go Authors standard license. (See the LICENSE file for details.)
