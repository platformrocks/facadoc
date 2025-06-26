
# FACADOC - Documentação de Arquivos Protegidos

## 📄 Descrição

Este projeto utiliza o padrão **FACADOC**, um cabeçalho visual em ASCII no formato de **faca**, para sinalizar arquivos que **não devem ser alterados manualmente**, pois são **gerados automaticamente** ou possuem regras de manutenção específicas.

O FACADOC é uma prática visual forte e direta para evitar alterações acidentais em arquivos críticos ou gerados por processos automáticos.



## 🔧 Quando Usar o FACADOC

Adicione o FACADOC no topo de arquivos que:

✅ São gerados por scripts, ferramentas ou pipelines automatizados.  
✅ Não devem ser modificados manualmente, sob risco de corromper o sistema ou gerar inconsistências.  
✅ Fazem parte de contratos, definições ou configurações críticas.  
✅ São artefatos de build ou exportações automáticas.  



## ✍️ Exemplo do FACADOC

```js
/**
 * 
 * ╔══════════════════════════════════════════════════════╗
 * ║  VEJA A FACA:                                        ║
 * ╚══════════════════════════════════════════════════════╝
 *
 *   ║\
 *   ║▓\
 *   ║▓▓║
 *   ║░▓║
 *   ║░▓║
 *  ▒▒▒▒▒▒
 *   ]█▒[
 *   ]█▒[
 * 
 * ╔══════════════════════════════════════════════════════╗
 * ║  NÃO MEXER!!!                                        ║
 * ║  NÃO ALTERE ESSE ARQUIVO, POIS ELE É GERADO          ║
 * ╚══════════════════════════════════════════════════════╝
 */
```

## 🏆 Veja um caso de uso 10 anos depois

[Assista o vídeo](/cases/case-10-anos-depois.mp4)




## ⚠️ Regras de Conduta

- **Nunca** edite manualmente arquivos que possuem o FACADOC.  
- Alterações devem ser feitas nos **scripts ou processos** que geram o arquivo.  
- Qualquer alteração direta será sobrescrita ou pode comprometer o sistema.  
- Se identificar um arquivo crítico sem FACADOC, avalie se ele deveria ter.  



## 🎯 Objetivo

- Reduzir o risco de erros humanos.  
- Facilitar a identificação de arquivos protegidos.  
- Manter a integridade de processos automatizados.  
- Criar um padrão visual simples e efetivo em toda a base de código.  



## 🛡️ Recomendação

Para equipes que geram arquivos automaticamente (configs, manifests, builds, etc.), padronize o uso do **FACADOC**. É simples, visual e altamente eficiente.

---
