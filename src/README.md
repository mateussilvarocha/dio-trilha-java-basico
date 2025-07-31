### Case 1: 
Vamos imaginar que um processo seletivo existe o valor base salarial de R$2.000,00 e o salário pretendido pelo candidato. Vamos elaborar um controle de fluxo onde:
- Se o valor salario base for maior que valor salários pretendido imprima LIGAR PARA O CANDIDATO;
- Senão Se o valor salário base for igual ao valor  salario pretendido, imprima: LIGAR PARA O CANDIDATO COM CONTRA PROPOSTA;
- Senão imprima: AGUARDANDO RESULTADO DEMAIS CANDIDATOS.


### Case 2: 
Foi solicitado que nosso sistema garanta que diante das inúmeras candidaturas sejam selecionados apenas no máximo 5 candidatos para entrevista inde o salários pretendido seja menor ou igual ao salários base.

-       1
        2 String [] candiatos = {"Felipe", "Marcia", "Julia", "Paulo", "Augusto"}
        3 

Metodo que simula o valor pretendido:

-       1
        2 import java.util.concurrent.ThreadLocalRandom;
        3
        4 static doble valorPrentendido(){
        5   return ThreadLocalRandom.current()nextDouble(1800,2200);
        6   }

### Case 3:
Agora é hora deImprimir a lista dos candidatos selecionados para disponibilizar para RH entrar em contato.

### Case 4: 
O Rh deverá realizar uma ligação com no máximo 03 tentativas para cada candidato selecionado e caso o candidato atenda, deve-se imprimir. 
- "CONSEGUIMOS CONTATO COM [CANDIDATO] APÓS [TENTATIVA] TENTATIVA(S)"
- do contrario imprima: "NÃO CONSEGUIMOS CONTATO COM O [CANDIDATO]"