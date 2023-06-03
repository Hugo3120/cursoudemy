*<h1 align="center"> Projeto criado em java OO "Tratando exceções". </h1>*
<h4> Nesse projeto foi feito três soluções diferentes, uma muito ruim até uma solução boa,
criando "exceções personalizadas".</h4>

Na primeira solução a lógica de validação foi criada no código principal, não
delegada à reserva.

Na segunda solução ainda ruim, foi usado o método retornando *"String"*,
A semântica da operação é prejudicada. Retornando uma String não tem nada
a ver com atualização de reserva, ainda não é possível tratar exceções em 
construtores, a lógica fica estruturada em condicionais aninhadas.

Na solução 3, foi tratado as exceções com boas práticas.
Podemos ver no código a seguir.

Classe Principal![20230603_133825](https://github.com/Hugo3120/cursoudemy/assets/88748776/9f52e5b5-c5e7-4f6e-8377-aaa8962d10b8)

Classe Entidade![20230603_133825](https://github.com/Hugo3120/cursoudemy/assets/88748776/b207433c-aa8f-42b9-8b81-38aea9a86dae)

Classe Domínio Exception![20230603_134900](https://github.com/Hugo3120/cursoudemy/assets/88748776/cf69b72f-8220-449f-bb8a-8a41bc23d9b2)


## Conclusão

Concluir que o modelo de exceções permite que erros sejam tratados de forma
consistente e flexível, usando boas práticas.

Aprendi que suas vantagens são:
* Lógica delegada.
* Construtores podem ter tratamento de exceções.
* Possibilidade de auxílio do compilador(Exception).
* Código mais simples. Não há aninhamento de condicionais a qualquer
momento que uma exceção for disparada, a execução é interrompida e cai no bloco catch correspondente.
* É possível capturar inclusive outras exceções de sistema.


Visite [Meu Linkedin](https://www.linkedin.com/in/hugo-leonardo-silva-66a604210/)

