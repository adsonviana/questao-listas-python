# O Osmar vai para...
## PROBLEM STATEMENT
Após uma série de descontentamentos com premiações internacionais, o Brasil decidiu criar uma cerimônia própria para prestigiar e celebrar as produções e as personalidades do país, e nomearam essa cerimônia de Osmar!  

![img_estatueta](https://github.com/adsonviana/questao-listas-python/blob/main/Sources/img_estatueta_osmar2.png?raw=true)  

Você, aluno do primeiro período do Centro de Informática, foi chamado para criar um programa que deve receber os votos dos jurados do Osmar e apresentar os resultados finais de quem ganhou cada categoria. **O programa deve utilizar obrigatoriamente o assunto de listas.**

As 3 principais e mais aclamadas categorias da noite são as que Fernanda Torres está concorrendo: Melhor Atriz, Melhor Meme e Representa o Brasil.  

# 🌟🏆Sobre as categorias principais🏆🌟

#### **Melhor Atriz**

As indicadas ao prêmio de Melhor Atriz são:
  
- Camila Pitanga  
- Fernanda Torres  
- Glória Pires  
- Taís Araújo  

![img_gloria](https://github.com/adsonviana/questao-listas-python/blob/main/Sources/img_gloria1.jpeg?raw=true)

#### **Melhor Meme**  

Os indicados ao prêmio de Melhor Meme são:  

- Bill  
- Fernanda Torres  
- Júlia  
- Nazaré  

Bill em “Bora, Bill”  
Júlia em “Meu nome é Júlia”  
Fernanda Torres em “O tempo está passando né, Sueli! Ó”  
Nazaré em “Nazaré confusa”  

![gif_fernanda](https://github.com/adsonviana/questao-listas-python/blob/main/Sources/gif_fernada2.gif?raw=true)

#### **Representa o Brasil**  

Os indicados ao prêmio de Representa o Brasil são:  

- Fernanda Torres  
- Ivete Sangalo  
- Rebeca Andrade  
- Selton Mello  

![img_rebeca](https://github.com/adsonviana/questao-listas-python/blob/main/Sources/img_rebeca1.jpg?raw=true)

## INPUT
- Logo no início, o programa receberá um valor inteiro que corresponde ao número de jurados presentes no evento.  
- O programa receberá em formato de string o nome da categoria atual, que será anunciada logo antes do início de cada votação dos jurados, pois a ordem das categorias não é fixa. Isso ocorrerá para cada uma das três categorias.  
- Após isso, o programa receberá o voto de cada jurado, que será um valor do tipo string com o nome do indicado no qual ele quer votar. Isso ocorrerá em cada uma das três categorias  

### **Observações**  
- Para que a votação seja válida devem existir pelo menos 3 e no máximo 20 jurados. Se o número de jurados for menor que 3 ou maior que 20 encerre o evento imediatamente.
- Devido a erros de digitação, alguns jurados podem escrever algumas letras em maiúsculo no meio das palavras, porém ainda assim esses votos devem ser aceitos. Por exemplo, Fernanda, fERNANDA e fERnAnDa são votos válidos para a contagem. Se o jurado digitar um nome que não corresponde a nenhum dos indicados à categoria atual, o programa deve, enquanto o voto continuar inválido, pedir um novo nome

## OUTPUT
- Se a quantidade de jurados for satisfatória, o programa deve mostrar a seguinte mensagem logo no início:  
   - “---------- Premiação Osmar 2025 ----------”
- Se o número de jurados for menor que 3 encerre o evento e imprima:
   - “Como é possível uma premiação não ter pelo menos 3 jurados? Vamos remarcar essa premiação.”
- Se o número de jurados for maior que 20 encerre o evento e imprima:
   - “Nem tem tanta cadeira assim na bancada dos jurados! Encerre o evento agora.”
- Se o jurado digitar um nome que não corresponde a nenhum dos indicados à categoria atual, o programa deve, enquanto o voto continuar inválido, imprimir:
   - “Nome não corresponde a nenhum dos indicados”

### **Ao final de cada categoria deve ser mostrado o nome do vencedor e a contagem de votos da categoria atual da seguinte maneira (antes do título da categoria há uma linha em branco também):**

### **Para a categoria Melhor Atriz:**

---------- Melhor Atriz ----------

O prêmio de Melhor Atriz vai para nome_vencedora!

Pontuações:  
Camila Pitanga: pontuacao_camila voto(s)!  
Fernanda Torres: pontuacao_fernanda voto(s)!  
Glória Pires: pontuacao_gloria voto(s)!  
Taís Araújo: pontuacao_tais voto(s)!  

### **Para a categoria Melhor Meme:**

---------- Melhor Meme ----------

O prêmio de Melhor Meme vai para nome_vencedor!

Pontuações:  
Bill: pontuacao_bill voto(s)!  
Fernanda Torres: pontuacao_fernanda voto(s)!  
Júlia: pontuacao_julia voto(s)!  
Nazaré: pontuacao_nazare voto(s)!  

### **Para a categoria Representa o Brasil:**

---------- Representa o Brasil ----------

O prêmio de Representa o Brasil vai para nome_vencedor!

Pontuações:  
Fernanda Torres: pontuacao_fernanda voto(s)!  
Ivete Sangalo: pontuacao_ivete voto(s)!  
Rebeca Andrade: pontuacao_rebeca voto(s)!  
Selton Mello: pontuacao_selton voto(s)!  

- Em caso de empate, o vencedor será aquele que tiver maior quantidade de letras no seu **nome como está escrito nas indicações aos prêmios**, sem considerar espaços em branco.
- Se ao final de tudo Fernanda Torres levar os três prêmios das categorias principais, o programa deve mostrar a seguinte mensagem:
   - “Fernandinha é a mais amada pelo povo brasileiro!”
- O programa sempre deve finalizar com a seguinte mensagem:
   - “A noite de cerimônia do Osmar está encerrada!”
