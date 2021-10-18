# BOT PARA ANALISAR DADOS DE VENDAS 
## Passos

1) Entrar no Drive (link)
2) Ir ate o local do relatorio (Dados de vendas)
3) Baixar o relatorio (Vendas - Dez.xlsx)
4) Calcular a soma da coluna  `Quantidade` e `Valor Final`
5) Enviar por e-mail

## Install Pyautogui e Pyperclip

* Instalar as bibliotecas `!pip install pyautogui` e  `!pip install pyperclip` basta execultar cada uma na cedula do Jupyter

## Importar Pyautogui e Pyperclip
* `import pyautogui` e `import pyperclip`

## import time 
Vamos importar o `time` caso variar o tempo de carregamento iremos colocar o <br> `pyautogui` e o `pyperclip` para ter um `delay` na execução  dos comandos.<br><br>

O `pyautogui.click`(x = 111, y = 111)<br>
Serve para informar a coordenada onde sera feito o click<br>
O `codigo` pode variar de monitor para monitor pois a coordenada muda.<br>

Para "corrigir" voce deve execultar o `time.sleep(5)` e `pyautogui.position()`<br>
Ao execultar voce tera 5 segundos para colocar o mouse em um lugar da sua tela e ao terminar a cédula ir te informar um `Point` que sera sua coordenada `Point(x=1318, y=206)`<br>

