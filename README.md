# Teste de viabilidade do projeto Donorade
Para validarmos se nossa proposta era viavel, realizamos uma V1 do nosso futuro site utilizando o Chat-GPT da Open-AI.

Obtivemos os seguintes resultados:
- Conseguimos integrar a AI ao site e passar o prompt para devolver ONGs que levam comida aos mais necessitados;
- Digitamos um endereço mais genérico (ex: Paulista, São Paulo, etc.), para sabermos o que devolveria (como nosso script pega os dados do input, leva para o python e concatena com o prompt, então era esperado a devolução de algo no HTML);
- Recebemos uma resposta do Chat-GPT (várias, já que o teste foi realizado dezenas de vezes), foi informado que o Chat-GPT não tem acesso as ONGs de cada região em tempo real, mesmo que tenha sugerido algumas outras instituições confiáveis para realizar doações;

Consideramos o teste um sucesso, pois, mesmo que não seja viável a utilização do Chat-GPT para a realizar a devolução de instituições confiáveis que visem ajudar os mais necessitados, tivemos o insight de que será necessário o projeto Donorade realizar parcerias com instituições que produzam IAs (talvez a própria Open-AI), para a produção de uma nova tecnologia que esteja voltada em buscar e devolver dados de ONGs oriundos de diversos cantos da internet.

## Para usar a aplicação
Para começar a usar este aplicativo, siga as etapas abaixo:

- Instale o Python em seu computador.
- Navegue até o diretório onde você clonou este repositório.
- Execute o comando `pip install -r requirements.txt` para instalar os pacotes Python necessários.
- Adicione sua chave de API OpenAI ao arquivo `app.py.` Você pode obter uma chave de API inscrevendo-se no programa de API da OpenAI.
- Execute o comando `python app.py` para iniciar o aplicativo.
