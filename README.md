# ip_renan.py
python3 ip_renan.py

nano ip_renan.py
import socket
import requests

def pegar_ip():
    return requests.get("https://api.ipify.org").text

print("Seu IP público:", pegar_ip())

cd pasta/onde/esta/o/arquivo
python ip_renan.py
