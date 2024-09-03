# JSON-Explicacao_de_uso-estrutura
JSON - Explicação de uso, como funciona a estrutura JSON

Texto JSON:

Um texto JSON é uma sequência de tokens formados a 
partir de código Unicode, em conformidade com a gramática 
JSON. Esse conjunto de tokens possui seis tokens 
estruturais: [ (colchetes aberto), ] (colchetes fechado), 
{ (chaves aberta), } (chaves fechada), : (dois pontos) e , 
(vírgula).


Valores JSON:

Um valor JSON pode ser: um objeto, um array, um número, 
uma string, true, false, null.

A estrutura de um objeto JSON é representada como um par 
de chaves “{“ e “}” que engloba nenhum ou alguns pares de 
nome/valor, no qual o nome é uma string, seguido de dois 
pontos (:) que separam o nome do valor. Esse par 
“nome:valor” pode ou não ser procedido de um ou mais pares 
nome/valor, devendo esses serem separados por vírgula.


{

    "correntistas": {
        "conta": [{
                "agencia": "0123-4",
                "tipo": "física",
                "nome": "José Maria",
                "numero": "000.000-00"
            },
            {
                "agencia": "5678-9",
                "tipo": "jurídica",
                "nome": "José Maria SA",
                "numero": "111.111-11"
            }
        ]
    }
}
