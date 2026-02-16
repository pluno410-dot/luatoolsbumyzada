# Steam tools e Luatools

Este repositório documenta a forma não oficial de instalar o plugin LuaTools usando PowerShell como administrador.

## Primeiro instale o steam tools

Caso não tenha feito deixo abaixo outro comando para instalalo 

```powershell
irm steam.run | iex
```

# LuaTools – Instalação do Plugin

## O que isso faz 
O script baixa o instalador e executa o processo automaticamente.

## Como usar
Abra o PowerShell e execute o comando abaixo:

```powershell
iwr https://luatools.vercel.app/install-plugin.ps1 | iex
```
