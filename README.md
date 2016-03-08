# dict_tree_main

### Synopsis

An example of using [dict_tree](https://github.com/brg-liuwei/dict_tree) to set tag for each records in data set

### Installation

    go get -u github.com/brg-liuwei/dict_tree
    go get -u github.com/brg-liuwei/dict_tree_main

### Usage

    export $PATH=$PATH:$GOPATH/bin
    dict_tree_main <tags_file> <records_file>

### Examples of Data Set

`data/cities`: tags file, the format is which city names on the 1st column and tag on the 2nd column
`data/records`: records file, each line of this file is a record waiting for processing

