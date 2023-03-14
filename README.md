# Analise-salarios
Web Scraping do Site Glassdoor

## Foi feita uma extração de dados atraves da Biblioteca Request e Beautifulsoup!!

  O intuito foi extrair empresas e Salario e criar um Base dados atraves desse Web Web Scraping, para complementar os dados foi usandas Bibliotecas de valores aleatorios, como: Faker, cpf_generator e random

## Todas as Libs Usadas: 
# importando as libs que iremos usar!
import pandas as pd
import numpy as np
import random 
import datetime

#Web Scraping
import requests
from bs4 import BeautifulSoup

#Gera dados Fakes
from faker import Faker
from cpf_generator import CPF
