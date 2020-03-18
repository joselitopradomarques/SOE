Para todas as questões, escreva os comandos correspondentes no terminal.

1. Escreva o texto "Ola mundo cruel!" em um arquivo denominado "Ola_mundo.txt". Apresente o conteúdo deste arquivo no terminal.
```C
more Ola_mundo
```
2. Apresente o nome de todos os arquivos e pastas na pasta 'root'.
```C
sudo -s
ls
exit ; Sair do super usuário
```

3. Apresente o tipo de todos os arquivos e pastas na pasta 'root'.
```C
sudo -s
file *
exit ; Para sair do super usuário
```

4. Apresente somente as pastas dentro da pasta 'root'.
```C
sudo -s
ls -d */
exit ; Para sair do super usuário
```
* filtra todos arwuivos e subdiretórios e o / restringe a listagem a subdiretórios

5. Descubra em que dia da semana caiu o seu aniversário nos últimos dez anos.
```C
NAO ESTA FEITO!!!!!!!!!!! 
```

Para as questões a seguir, use a pasta no endereço https://github.com/DiogoCaetanoGarcia/Sistemas_Embarcados/raw/master/Questoes/02_Intro_Linux_arqs.zip

6. Liste somente os arquivos com extensão .txt.
```C
cd Downloads
find . -type f name "*.txt"
```
7. Liste somente os arquivos com extensão .png.
```C
cd Downloads
find . -type f name "*.png"
```

8. Liste somente os arquivos com extensão .jpg.
```C
cd Downloads
find . -type f name "*.jpg"
```

9. Liste somente os arquivos com extensão .gif.
```C
cd Downloads
find . -type f name "*.gif"
```

10. Liste somente os arquivos que contenham o nome 'cal'.
```C
cd Downloads
find . -type f name "*.jpg"
```

11. Liste somente os arquivos que contenham o nome 'tux'.
```C
cd Downloads
ls | grep tux
```

12. Liste somente os arquivos que comecem com o nome 'tux'.
```C
cd Downloads
ls | grep tux*
```
- Caso queira os nomes que finalizam com tux, procure por: 
```C
cd Downloads
ls | grep tux*
```
