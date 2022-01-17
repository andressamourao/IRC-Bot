---

Meu primeiro chatbot!

---

Olá, esse é o meu primeiro projeto que utiliza alguma forma de inteligência artificial. Buscando fazer novos projetos simples com o python, encontrei o canal do Youtube hashtah programação. Em vídeo curto de 30 minutos, aprendi um pouco de virtualização, uma vez que foi preciso criar um novo ambiente e sobre como um chatbot funciona! Foi uma ótima experiência.

---

Mas andressa, por que é importante criar um ambiente virtual novo?

---

O ambiente virtual é excelente quando se quer combinar compatibilização com estabilidade. No nosso caso, usamos o python na versão 3.6 que era compatível com o chatterbot. Não há interferência do ambiente externo com o interno e vice-versa.

---

ATENÇÃO

---

AH! Essa parte é importante, no tutorial é explicado que há uma incompatibilidade na versão atual do chatterbot com a ferramenta spacy, por isso, devemos adicionar esta parte do código.

from spacy.cli import download

download("en_core_web_sm")

class ENGSM:
ISO_639_1 = 'en_core_web_sm'
