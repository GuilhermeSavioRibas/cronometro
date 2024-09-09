# Cronômetro com Comando de Voz e Botões

Este é um projeto de cronômetro web que utiliza comandos de voz e botões para iniciar, reiniciar e parar o cronômetro. O cronômetro é projetado para ser utilizado em ambientes de Service Desk, auxiliando os analistas a monitorar o tempo de espera dos clientes. Com frases específicas de comando, o cronômetro é iniciado, pausado ou reiniciado automaticamente.

## Funcionalidades

- **Comandos de Voz**: O cronômetro responde a frases como "um momento", "mais um momento" para iniciar ou reiniciar, e "obrigado por aguardar" para parar.
- **Botões**: Também é possível controlar o cronômetro manualmente com os botões de **Iniciar**, **Resetar** e **Parar**.
- **Alarme Sonoro**: Toca um som (arquivo `beep.mp3`) ao atingir 1 minuto e 50 segundos.
- **Interface Simples**: Interface visual amigável com exibição do tempo decorrido e status.
- **Compatível com Web Speech API**: O cronômetro utiliza a API de reconhecimento de voz disponível em navegadores compatíveis, como Google Chrome.

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    cd nome-do-repositorio
    ```

2. Abra o arquivo `index.html` em seu navegador preferido (de preferência, Google Chrome).

3. Certifique-se de que seu microfone esteja ativado para utilizar os comandos de voz.

4. Utilize as seguintes frases para controlar o cronômetro:
   - **Iniciar/Reiniciar Cronômetro**: Diga "um momento", "mais um momento", "só um momento" ou frases semelhantes.
   - **Parar Cronômetro**: Diga "obrigado por aguardar", "muito obrigado por esperar", "agradeço pela paciência" ou frases semelhantes.

5. O cronômetro também pode ser controlado manualmente pelos botões.

## Frases Suportadas

- **Para iniciar ou reiniciar o cronômetro**:
    - "um momento"
    - "mais um momento"
    - "só um momento"
    - "um instante"
    - "só mais um momento"
    - "só mais um instante"
    - "um momentinho"
    - "um pouquinho de tempo"
    - Entre outras variações.

- **Para parar o cronômetro**:
    - "obrigado por aguardar"
    - "muito obrigado por ter aguardado"
    - "agradeço pela paciência"
    - "valeu por esperar"
    - "muito obrigado por esperar"
    - Entre outras variações.

## Arquivo de Beep

Certifique-se de que o arquivo de som `beep.mp3` esteja no mesmo diretório que o arquivo HTML para que o alarme sonoro toque corretamente após 1 minuto e 50 segundos.

## Requisitos do Sistema

- Navegador compatível com a API Web Speech (Recomendado: **Google Chrome**).
- Microfone funcionando para detecção de comandos de voz.

## Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma nova branch:
    ```bash
    git checkout -b minha-nova-feature
    ```
3. Faça suas alterações e commit:
    ```bash
    git commit -m "Adiciona nova feature"
    ```
4. Envie suas alterações:
    ```bash
    git push origin minha-nova-feature
    ```
5. Abra um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Créditos

Desenvolvido por Guilherme Ribas.
