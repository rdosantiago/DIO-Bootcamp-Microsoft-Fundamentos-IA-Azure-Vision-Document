# DIO-Bootcamp-Microsoft-Fundamentos-IA-Azure-Vision-Document
Atividade: Transformação de imagens em Dados no Azure ML

# Passo-a-Passo para Configurar o Azure Vision + Document para Análise OCR

1. **Acessar o Portal do Azure**
   - Abra o Portal do Azure e faça login com suas credenciais.
   - Navegue até a seção "Criar um recurso".

2. **Criar um Serviço Azure Cognitive Services**
   - No menu, selecione "Inteligência Artificial + Machine Learning".
   - Clique em "Cognitive Services" e, em seguida, em "Visão Computacional".
   - Preencha os detalhes, como nome do serviço, assinatura, grupo de recursos e região.
   - Clique em "Revisar + criar" e, depois, em "Criar".

3. **Configurar o Serviço de Visão Computacional**
   - Após a criação do serviço, acesse-o no Portal do Azure.
   - No painel de navegação, selecione "Chaves e Endpoint" e copie a chave de API e o endpoint fornecidos.

4. **Configurar o Azure Vision + Document no Azure AI Foundry**
   - Acesse o Azure AI Foundry e vá até o "Playground de Idiomas".
   - Selecione "Configurar um novo projeto".
   - Escolha "Análise de Documentos" e forneça um nome ao projeto.

5. **Carregar Imagens de Amostra**
   - No painel do projeto, clique em "Adicionar documento".
   - Carregue as imagens de amostra que deseja analisar para reconhecimento de texto (OCR).

6. **Configurar a Análise OCR**
   - Selecione as imagens carregadas e configure os parâmetros de análise OCR.
   - Adicione a chave de API e o endpoint do serviço de Visão Computacional.

7. **Executar a Análise OCR**
   - Clique em "Executar análise" para iniciar o processo de reconhecimento de texto (OCR).
   - O Azure Vision + Document analisará as imagens e extrairá o texto contido nelas.

# Insights e Possibilidades do Uso do OCR com Azure Vision + Document

- **Precisão e Eficiência**: O OCR do Azure Vision + Document oferece alta precisão na extração de texto, mesmo em imagens complexas.
- **Automatização de Processos**: Facilita a automação de tarefas administrativas, como digitalização de documentos e arquivamento.
- **Capacidade Multilíngue**: Suporta diversos idiomas, permitindo a análise de documentos em várias línguas.
- **Integração com Outros Serviços**: Pode ser integrado com outros serviços do Azure para análises mais abrangentes e enriquecimento de dados.
- **Acessibilidade Melhorada**: Converte texto em voz ou em formato compatível com leitores de tela, melhorando a acessibilidade para pessoas com deficiência visual.

# Aprendizado

Durante o processo de configuração do Azure Vision + Document para realizar uma análise OCR, aprendi diversas etapas importantes e adquiri conhecimentos valiosos. Primeiro, entendi como criar um serviço no Azure Cognitive Services e configurar o serviço de Visão Computacional, onde obtive as chaves de API e o endpoint necessários.

Carregar as imagens de amostra e configurar os parâmetros de análise OCR foi uma etapa crucial, onde percebi a importância de ajustar corretamente as configurações para garantir uma análise precisa. Aprendi a utilizar o Playground de Idiomas no Azure AI Foundry para integrar o Azure Vision + Document e realizar a análise OCR.

Executar a análise OCR e extrair o texto das imagens me proporcionou uma visão clara de como a tecnologia pode ser aplicada para automatizar tarefas e melhorar a eficiência na digitalização e arquivamento de documentos. Também compreendi as vantagens de utilizar o OCR do Azure Vision + Document, como a precisão na extração de texto, a capacidade multilíngue e a integração com outros serviços do Azure.

No geral, essa experiência educativa me ajudou a compreender melhor as capacidades e possibilidades do OCR baseado em IA, e como essa ferramenta pode ser aplicada em diversos contextos para facilitar o trabalho e melhorar a acessibilidade.
