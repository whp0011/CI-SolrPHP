CodeIgniter Solr PHP Client
===========================

This is a simple library for CodeIgniter to interface with Solr. I am not the original author of the code, I've just made it compatible with codeigniter.

This CI library is based on [Apache Solr PHP Client](https://code.google.com/p/solr-php-client/)

Usage
=====

Put the files from this repo into application/libraries/solr.

This library is very simple to install, simply load it the way you do any other CI library and pass it an array of parameters (optional).

    $this->load->library('solr',array(
        'port' => 8983,
        'path' => '/solr/posts/'
    ));