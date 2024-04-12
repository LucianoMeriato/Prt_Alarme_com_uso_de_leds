Alunos
Eric Darakjian
RM557082

Luciano Henrique Meriato Junior
RM554546

Pedro Pawlik Ferrari
RM556968

Pietro Vitor Pezzente
RM557283

# Prt_Alarme_com_uso_de_leds
Esse repositorio tem como intuito apresentar o projeto realizado pelos alunos : Erick , Luciano, Pedro Pawlik, Pietro

Sistema de Semáforo e Alerta Sonoro com Arduino



Componentes usados para desenvolvimento do sistema
Arduino Uno (ou similar)
1 LED Vermelho
1 LED Amarelo
1 LED Verde
1 Buzzer
1 Resistor de 10k ohm
3 Resistores de 220 ohm
1 Sensor LDR (Light Dependent Resistor)
Jumpers
Diagrama de Conexões:
LED vermelho -> Pino 13
LED amarelo -> Pino 12
LED verde -> Pino 11
Buzzer -> Pino 9
Sensor LDR -> Pino A0
Resistor de 10k ohm -> Conectar um lado ao GND e o outro ao pino A0 do Sensor LDR
Resistor de 220 ohm -> Conectar um lado ao LED vermelho, amarelo e verde, e o outro lado ao GND

Modo de funcionamento do código:
Basicamente seu funcionamento se baseia da seguinte forma: O código ira ler continuamente a entrada do sensor LDR detectando a luminosidade, que se for acima de 700 ligara o led vermelho, desta forma então fazendo com que o buzzer emita um som continuo e agudo, vale lembrar que enquanto o led vermelho esta ligado ambos os leds são desligados 
Agora caso a luminosidade esteja entre 600 e 700 o LED amarelo é ligado, enquanto os LEDs vermelho e verde são desligados.
E se a luminosidade for abaixo de 600, o LED verde é ligado, enquanto os LEDs vermelho e amarelo são desligados.


Como fazer a instalação:
Para poder fazer a instalação e conexão você deve seguir os seguintes passos que são bem simples!

Basicamente antes de tudo você já deve estar com todos os componentes em mãos e montados de acordo com o projeto que foi desenvolvido no ThinkerCad
Feito tudo isso e com todos os materiais em mãos você devera conectar o Arduino no computador -> abrir a aplicação do Arduino -> importar o projeto -> e passo final que é executar e conferir se o projeto está funcionando de acordo como o esperado 
