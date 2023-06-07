# tfcs (Telegram Free Cloud Storage)

## Description

Use a closed network of 2 or more Telegram accounts to share binary files
between them. The binary files are homogenous[0] encrypted blocks that store
files

## Glossary

[0] homogenous
Blocks are binary files that conform to a limted range file size
(maybe 1MB - 4MB or 5MB-50MB). Files that are uploaded are striped to these 
blocks and the blocks are two-way encrypted with a gpg key.
