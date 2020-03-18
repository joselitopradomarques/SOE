Para todas as questões, escreva os comandos correspondentes no terminal.

1. Escreva o texto "Ola mundo cruel!" em um arquivo denominado "Ola_mundo.txt". Apresente o conteúdo deste arquivo no terminal.
```Shell
echo Ola mundo cruel! > Ola_mundo.txt
more Ola_mundo
```
2. Apresente o nome de todos os arquivos e pastas na pasta 'root'.
```Shell
ls /
```

3. Apresente o tipo de todos os arquivos e pastas na pasta 'root'.
```Shell
ls -l /
```

4. Apresente somente as pastas dentro da pasta 'root'.
```Shell
cd /
ls -d -l */
```
* filtra todos arquivos e subdiretórios e o / restringe a listagem a subdiretórios

5. Descubra em que dia da semana caiu o seu aniversário nos últimos dez anos.
```Shell
NAO ESTA FEITO!!!!!!!!!!! 
```

Para as questões a seguir, use a pasta no endereço https://github.com/DiogoCaetanoGarcia/Sistemas_Embarcados/raw/master/Questoes/02_Intro_Linux_arqs.zip

6. Liste somente os arquivos com extensão .txt.
```Shell
ls -l *.txt
```
7. Liste somente os arquivos com extensão .png.
```Shell
ls -l *.png
```

8. Liste somente os arquivos com extensão .jpg.
```Shell
ls -l *.jpg
```

9. Liste somente os arquivos com extensão .gif.
```Shell
ls -l *.gif
```

10. Liste somente os arquivos que contenham o nome 'cal'.
```Shell
ls -l *cal*
```

11. Liste somente os arquivos que contenham o nome 'tux'.
```Shell
ls -l *tux*
```

12. Liste somente os arquivos que comecem com o nome 'tux'.
```Shell
ls -l tux*
```
- Caso queira os nomes que finalizam com tux, procure por: 
```Shelle
ls -l *tux
```
