## [4.2.1] - 30-06-2025
- Correção: Tratamento de erros que acontecem em casos onde o arquivo não pode ser carregado.
- Correção: Identificação de documentos aceitos corrigida.

## [4.2.0] - 24-03-2025
- Melhoria: Atualização de libs para suporte android 15 (16k).
- Melhoria: Atualização mínimo sdk suportado 24.
- Melhoria: Atualização java 17.
- Melhoria: Atualização lib Camerax de 1.1.0 para 1.4.0.
- Melhoria: Substituição lib TFLite para mediapipe tasks-vision 0.10.20
- Melhoria: Atualização lib guava 33.4.0

## [4.1.0] - 10-03-2025
- Melhoria: Adição da captura de outros documentos.
- Melhoria: Adição do upload de outros documentos digitais.

## [4.0.10] - 31-01-2025
- Melhoria: Adição da possibilidade de customização no Título da Tela de Preview.

## [4.0.9] - 06-01-2025
- Melhoria: Adicionado DexGuard.

## [4.0.8] - 04-12-2024
- Correção: Inicialização do componente no Android 15.
- Correção: Protocolos sem ID.

## [4.0.7] - 21-10-2024
- Correção: adição de novo certificado.

## [4.0.6] - 04-10-2024
- Correção: Validação de emuladores.

## [4.0.5] - 18-07-2024
- Correção: validação sslpinning.

## [4.0.4] - 15-07-2024
- Melhoria: Ajustar o retorno do objeto do callback (incluindo "statusRequest").
- Correção(hotfix): Ajustar o retorno do objeto do callback em caso de sucesso ("docType").

## [4.0.3] - 01-07-2024
- Melhoria: Inclusão da flag 'spoofValidationExceptions' para exceções de spoof.

## [4.0.2] - 19-06-2024
- Correção(hotfix): Ajustar no processo de CNHDigital.

## [4.0.1] - 18-03-2024
- Correção(hotfix): Adicionado crop de documentos do lado AB no fluxo de captura sem validação.
- Correção(hotfix): Ajustar descrição no processo de captura de CNHCel e CNHDigital.
- Melhoria: Inclusão da flag 'playCaptureSound'.

## [4.0.0] - 29-02-2024
- Melhoria: Alterações dos layouts para Nova Experiência.
- Melhoria: Melhorias no processo de captura.
- Melhoria: Permitir customização dos parâmetros de textos e cores.
- Melhoria: Depreciação das flags 'timeoutCapturaManual' e 'orientacaoCaptura'.
- Melhoria: Inclusão da flag 'tentativasExibicaoBotao'.

## [3.3.3] - 21-02-2024
- Correcao: Mudança no bundle para evitar o erro TooLargeException.
- Melhoria: Inclusão de novas regras para verificar se app executa em emulador.

## [3.3.2] - 07-12-2023
- Melhoria: Adicionado novo certificado sslpinning.

## [3.3.1] - 29-11-2023
- Correcao: ajustes no tratamento do bitmap, locationInfo (GPS) e cast fragment 
- 
## [3.3.0] - 26-10-2023
- Melhoria: Alteração da API de tipificação do upload da CNH Digital.
- Melhoria: Coleta de metadados do processo de upload da CNH Digital.
- Melhoria: Adicionado Flag (Spoof) para validação foto de foto de um documento 
- Melhoria: Tratamento, correção e adição de novos erros
- Melhoria: Ajustar o retorno do objeto de erro do callback(incluindo docType e image)
- Correção: Ajustes instruções de captura sobrepostas com moldura de enquadramento


## [3.2.1] - 09-10-2023
- Melhoria: Permitir customização do título na tela de Sucesso.

## [3.2.0] - 04-10-2023
- Melhoria: Ajuste retorno de call-back.
- Melhoria: Permitir customização dos textos da tela de Instrução de Upload da CNH Digital.
- Melhoria: Permitir customização dos textos da tela de Upload da CNH Digital.
- Melhoria: Removido ícone de fechar da tela de sucesso.
- Melhoria: Tratamento dos erros de comunicação e conexão.

## [3.1.3] - 29-08-2023
- Melhoria: Customização da tela de Sucesso.
- Melhoria: Customização da tela de Erro.

## [3.1.2] - 24-08-2023
- Correção: Tratamentos no ciclo de vida do aplicativo.

## [3.1.1] - 15-08-2023
- Correção: Tratamentos de null exception.
- Correção: Validação do tamanho de arquivo da CNH Digital.

## [3.1.0] - 31-05-2023
- Melhoria: Análise e tipificação de documento localmente.
- Melhoria: Upadate modelo de análise.
- Melhoria: Depreciação do uso do acelerômetro.
- Melhoria: Ajustes layouts tablet
- Melhoria: Removido lib tflite gpu.

## [3.0.0] - 27-04-2023
- Melhoria: Remoção da biblioteca MLKit.
- Melhoria: Inclusão da biblioteca TFLite.
- Melhoria: Upgrade de biblioteca Camerax para 1.1.0
- Melhoria: Inclusão de biblioteca viewbinding 7.1.2
- Melhoria: Alteração de layout da tela de seleção.
- Melhoria: Alteração de layout da tela de sucesso.
- Melhoria: Alteração na ordem de exibição da tela de seleção do documento.
- Melhoria: Inclusão do fluxo de cnh digital.
- Melhoria: Inclusão do fluxo de finalizar jornada.
- Melhoria: Agrupamento de CNH Celulose.
- Correção: Corrigir o envio do arquivo de metadados para o serviço.

## [2.0.5] - 12-04-2023
- Correção: Configuração de cor backgroung tela loading.
- Melhoria: Configuração de cor de texto tela loading.
- Melhoria: Configuração de texto tela loading.

## [2.0.4] - 10-03-2023
- Correção: Remoção de lib logging-interceptor para downgrade de lib okhttp.

## [2.0.3] - 08-03-2023
- Correção: downgrade lib Camerax para 1.0.0 para utilização compileSdk 31.

## [2.0.2] - 24-02-2023
- Melhoria: Retorno de id -2 ao retorno quando o documento não for identificado.
- Melhoria: Adicionado flag (telaConfirmacaoDeSaida) para habilitar/desabilitar tela de confirmação da saída.

## [2.0.1] - 03-02-2023
- Melhoria: atualização lib Camerax para 1.2.0 para correções da própria lib.
- Melhoria: inclusão da lib glide para otimização da memória na visualização de imagem.
- Correção: redução da imagem capturada em dispositivo com baixa quantidade de memória.
- Correção: tratamentos de null exception.
- Correção: substituído imagens xml para png e enviar erro em versões do android mais antigas.
- Correção: remoção da vibração no processo de captura.

## [2.0.0] - 27-01-2023
- Melhoria: atulização de layout para nova experiência com acessibilidade.
- Melhoria: ícones de telas customizáveis.
- Melhoria: remoção de ícone de tipo de documento na tela de captura.
- Melhoria: inclução de ícone de confirmação para captura.
- Melhoria: inclução de vibração no processo de captura.

## [1.8.0] - 18-01-2023
- Melhoria: atulização lib MLKit para 17.0.0.

## [1.7.3] - 29-12-2022
- Correção: convert o campo events para string.
- Correção: libera objeto timer de captura evitar memory leak.

## [1.7.2] - 26-12-2022
- Correção: Ajuste na criação dos construtores das Fragments.

## [1.7.1] - 20-12-2022
- Correção: Ajuste na criação dos construtores das Fragments.

## [1.7.0] - 30-11-2022
- Melhoria: Retorno da flag SSLPinning.
- Melhoria: Inclusão de novo certificado.

## [1.6.6] - 24-11-2022
- Correção: Ajustes processo de finalizar câmera.

## [1.6.5] - 22-11-2022
- Correção: Ajustes tratamento de objetos null.
- Correção: Ajustes na execução do talk back.

## [1.6.4] - 06-10-2022
- Correção: Retorno da flag de luminosidade.
- Correção: Mudança na forma como é verificada a luminosidade da imagem capturada.
- Correção: Botão de captura manual sem execução de auto focus

## [1.6.3] - 28-09-2022
- Correção: adicionando -repackageclasses e consumer-rules.

## [1.6.2] - 21-09-2022
- Correção: Erro null no processo de tentativas.

## [1.6.1] - 15-09-2022
- Correção: Mudança de nomenclatura de xml de animation.

## [1.6.0] - 09-09-2022
- Melhoria: Implementação de crop via api.
- Correção: Remoção ícones launcher no sdk.
- Correção: Tratamento de objeto null em cameraControl.
- Melhoria: Retornar id "-1" para outros documentos.
- Melhoria: Implementação flag (tentativasDeCaptura) de numero máximo de tentativas de captura.
- Melhoria: Implementação de crop via mlkit em outros documentos em captura automatica.
- Melhoria: Aproximar mais o documento quando o lado aceito for a ou b.
- Melhoria: Depreciação da flag SSLPinning.
- Melhoria: Alterado texto padrão de erros.
- Melhoria: Mudança flag (verificarLuminosidade) depreciada(Validação via api).

## [1.5.1] - 28-07-2022
- Correção: Alteração icone padrão de captura manual.

## [1.5.0] - 28-07-2022
- Melhoria: Alteração de nomenclarura (erroCallbackListener) para (documentCallbackListener)
- Melhoria: Retornar erros e sucesso via call back (documentCallbackListener)
- Melhoria: Adicionado tipoDeCaptura no retorno do documentCallbackListener
- Melhoria: flag (capturaManual) para habilitar processo de captura manual.
- Melhoria: flag (orientacaoCaptura) para habilitar a mudança na orientação do layout de captura entre a forma "portrait" e "landscape"
- Melhoria: Alteração de nomenclarura da cores (brscan_background_captura, brscan_default_captura e brscan_highlight_captura) por (brscan_documento_background_captura, brscan_documento_default_captura e brscan_documento_highlight_captura) respectivamente.
- Melhoria: Alteraçõa de cores padrão (
  brscan_documento_highlight_captura = #00AF7D,
  brscan_documento_default_captura = #FFFFFF,
  brscan_documento_background_captura = #B2000000,
  brscan_documento_icone_captura_botao_fechar = #FFFFFF e
  brscan_documento_box_texto_orientacao = #00000000)
- Melhoria: Alteração do tamanho da fonte de brscan_documento_tamanho_texto_orientacao para 16px
- Correção: verificação de uso de vpn.


## [1.4.0] - 11-07-2022
- Melhoria: Retornar erros via call back (erroCallbackListener)
- Melhoria: Alterar o tamanho da imagem para envio ao type document
- Melhoria: Realizar a captura do documento com o device estabilizado
- Melhoria: Remoção de flag auto-focus do manifest

## [1.3.1] - 29-06-2022
- Correção: flag (tipoRetorno) valor default base64.

## [1.3.0] - 27-06-2022
- Melhoria: Adicionado o envio de metadados para analise e processamento.

## [1.2.10] - 31-05-2022
- Correção: Processo com delay 0 e tempo de captura do documento fixo.
- Melhoria: Modificado flag (tempoDelayMensagem) para 0ms como default
- Melhoria: Mudança flag (tempoDelayMensagem) depreciada
- Melhoria: Adicionado flag (tokenTentativa) define quantos tokens extra podem ser usados(0 default)
- Melhoria: Adicionado variáveis para obtenção de métricas.

## [1.2.9] - 10-05-2022
- Correção: Retorno para tela que chamou a tela de captura ao acionar botão de fechar.

## [1.2.8] - 05-05-2022
- Melhoria: Alteração apontamento para validar chave document.brscan.com.br/v1/.
- Melhoria: Adicionado flag (segurancaExtraEmulatorCheck) para validar se o dispositivo é um emulador.

## [1.2.7] - 29-04-2022
- Correção: Problema ao iniciar captura em dispositivos mais antigos.

## [1.2.6] - 25-04-2022
- Melhoria: Adicionado flag (tempoDelayMensagem) define o tempo de exibição entre as mensagem de processo(2000ms default).
- Melhoria: Adicionado flag (acessibilidade) que habilita recurso de acessibilidade A+
- Melhoria: Incluído customização(via xml) de cores texto e caixa de orientações na tela de captura.
- Melhoria: Incluído customização(via xml) de tamanho texto de orientações na tela de captura.
- Correção: Aumentado range para captura de imagem.

## [1.2.5] - 14-04-2022
- Correção: Remoção de meta do retorno de tipo "base64" data:image/jpeg;base64.

## [1.2.4] - 12-04-2022
- Melhoria: Otimização no uso de memória.
- Melhoria: Adicionado Label (RG, CNH ou documento) e o lado (Frente, Verso e Aberto) quando informado.

## [1.2.3] - 06-04-2022
- Correção: Redução de imagens para exibição em dispositivos com pouco recurso.

## [1.2.2] - 04-04-2022
- Correção: Erro na exibição das imagens em dispositivos com pouco recurso.
- Melhoria: Adicionado flag (scoreMinimo) para receber o valor de score mínimo aceito (0 a 100 default 60)
- Melhoria: Incluído meta do retorno de tipo "base64" data:image/jpeg;base64.
- Melhoria: No retorno com erro será retornado o Código do erro, iD da analise e a Descrição.
- Melhoria: Incluído parametrização da cor do backgroung do frame de loading
- Melhoria: Incluído parametrização da cor do botão dos frames.
- Melhoria: Incluído parametrização da cor do Check das instruções.

## [1.2.1] - 28-03-2022
- Melhoria: Adicionado flag (retornarErros) retonar todos os erros para aplicação cliente.
- Melhoria: Mudança flag (segurancaExtra) depreciada.
- Melhoria: Adicionado flag (segurancaExtraRootCheck) para validar se o dispositivo está no modo root.
- Melhoria: Adicionado flag (segurancaExtraSslPinning) para validar ssl pinning.
- Correção: Ajuste na captura para evitar desfoque.

## [1.2.0] - 17-03-2022
- Melhoria: Alteração apontamento para novo serviço document.brscan.com.br/v1/.
- Melhoria: Adicionando no objeto de retorno o id da captura.
- Melhoria: Adicionado botão de fechar na tela inicial (quando wizard for true) que possibilitar sai do sdk.
- Melhoria: Alteração no botão de fechar da tela de captura para um x da cor preta.
- Melhoria: Alteração da cor da moldura da tela de captura para cor secondary (magenta).
- Melhoria: Remoção de validação por score e Depreciação da flag (scoreMinimo).

## [1.1.5] - 09-03-2022
- Melhoria: Melhoria: Alteração de titulo tela inicial

## [1.1.4] - 23-02-2022
- Melhoria: Adicionado flag (scoreMinimo) para receber o valor de score mínimo aceito

## [1.1.3] - 16-02-2022
- Correção verificação de lado b e ab.

## [1.1.2] - 16-02-2022
- Correção label de informação de documento (tipo e lado).

## [1.1.1] - 10-02-2022
- Correção erro de documento não permitido com flag validaDocumento false.

## [1.1.0] - 09-02-2022
- Melhoria: Adicionado flag (swiper) para habilitar/desabilitar telas de instruções para captura com iconografia.
- Melhoria: Adicionado flag (telaSelecaoDocumento) para habilitar/desabilitar tela de escolha do tipo de documento.
- Melhoria: Adicionado imagem cropada na tela de confirmação do documento.
- Melhoria: Retorno de imagens em base64 em baixa resolução.
- Melhoria: Retorno de boundingbox da imagem.
- Melhoria: Adicionado flag (resolucao) para informar o tipo de resolução(low, hd e original) da imagem a ser salva.
- Melhoria: Adicionado flag (ladoDocumentoAceito) para capturar apenas um lado específico.
- Melhoria: Remoção de imagens capturadas anteriormente pela lib.
- Melhoria: Adicionado tela de erro de conexão com opções de enviar novamente ou cancelar o processo.
- Melhoria: Adicionado flag (telaPreview) para habilitar/desabilitar telas de Preview
- Melhoria: Adicionado flag (tipoRetorno) para escolher entre base64 ou path do arquivo
- Melhoria: Não salva imagem quando o tipo de retorno é base64
- Melhoria: Mudança no objeto de retorno (removendo campos path e base64 e adicionando campo imagem)
- Melhoria: Adicionado flag (configuracaoTexto) para receber os textos de customização

## [1.0.30] - 14-01-2022
- Correção: Ajuste na função de habilitar/desabilitar verificação de luminosidade.

## [1.0.29] - 14-01-2022
- Melhoria: Adicionado flag para habilitar/desabilitar verificação de luminosidade.

## [1.0.28] - 22-11-2021
- Melhoria: Adicionado tela de preview e confirmação de captura

## [1.0.27] - 17-11-2021
- Melhoria: Customização de fonte.
- Melhoria: Customização da tela de captura. 