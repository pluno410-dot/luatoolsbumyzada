# LuaTools – Instalação do Plugin

Este repositório documenta a forma oficial de instalar o plugin LuaTools usando PowerShell.
Primeiro instale o steam tools caso não tenha feito

irm steam.run | iex

## O que isso faz 
O script baixa o instalador e executa o processo automaticamente.

## Como usar
Abra o PowerShell e execute o comando abaixo:

```powershell
iwr https://luatools.vercel.app/install-plugin.ps1 | iex

