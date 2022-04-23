# KXMLParser
Rest-Framework Parser Convert xml to json

##Getting Started
#### Dependencies
You need Python 3.7 or later

You also need json and xmltodict packages available from PyPI, if you have pip just run:
pip install xmltodict

####Instalation

pip install KXMLParser

Setting parser, edit settings.py :

REST_FRAMEWORK = {
    'DEFAULT_PARSER_CLASSES': [
        'KXMLParser.parsers.XMLParser',
        
    ],
}



## Features
- File structure for PyPI packages
- Setup with package informations
- License example

