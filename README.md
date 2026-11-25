# Verificador de Core Web Vitals e Desempenho Web

[![Verificador Core Web Vitals](https://img.shields.io/badge/TAVARDT-Core%20Web%20Vitals-5b3cf5.svg)](https://tools.tavardt.com/pt/verificador-core-web-vitals/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)]

Auditoria tecnica de TTFB, recursos de bloqueio de renderizacao e estabilidade visual sob normas W3C.

***

## Capacidades de Auditoria de Core Web Vitals

* **Análise de Resposta do Servidor e TTFB**: Avaliacao rigorosa do Time to First Byte e tempos de latencia de rede.
* **Deteccao de Elementos de Bloqueio de Renderizacao**: Mapeamento de ficheiros CSS e scripts externos que adiam a pintura inicial do conteudo.
* **Prevencao de Instabilidade de Layout (CLS)**: Verificacao de atributos de tamanho em imagens e recursos multimidia.
* **Auditoria de Compressao**: Confirmacao do uso de algoritmos Brotli e Gzip nos cabeçalhos de resposta HTTP.
* **Indice de Eficiencia de Carregamento**: Pontuacao tecnica de 0 a 100 com indicacoes de mitigacao.

***

## Instalação e Execucao

Requer Python 3.8 ou superior, utilizando a biblioteca padrao.

```bash
git clone https://github.com/TAVARDT-Portugal/core-web-vitals-tester-pt.git
cd core-web-vitals-tester-pt
python cwv_tester.py https://empresa.pt
```

Para inspeção com saída estruturada em JSON:

```bash
python cwv_tester.py https://empresa.pt -json
```

***

## Consultoria em Desempenho Web e Aceleracao

Para projetos de otimizacao tecnica alinhados com Normas Europeias de Desempenho Web e W3C, consulte a equipa da **TAVARDT Portugal**.

## Links Úteis

* **Portal Corporativo:** https://ag.tavardt.com/pt/
* **Suíte de Diagnósticos:** https://tools.tavardt.com/pt/
* **Contacto Técnico:** https://ag.tavardt.com/pt/contacto/

***

### Licença
Distribuído sob a Licença MIT.

***

© 2026 TAVARDT Portugal. Todos os direitos reservados. Soberania e Defesa de Infraestrutura.
