
# FACADOC - Documentação de Código Protegido

O padrão **FACADOC**, um cabeçalho visual em ASCII no formato de **faca**, para sinalizar arquivos que **não devem ser alterados manualmente**, pois são **gerados automaticamente** ou possuem regras de manutenção específicas.

O FACADOC é uma prática visual forte e direta para evitar alterações acidentais em códigos críticos (e cagados) ou gerados por processos automáticos.



## 🔧 Quando Usar o FACADOC

Adicione o FACADOC no topo que:

✅ São gerados por scripts, ferramentas ou pipelines automatizados.  
✅ Não devem ser modificados manualmente, sob risco de corromper o sistema ou gerar inconsistências.  
✅ Fazem parte de contratos, definições ou configurações críticas.  
✅ São artefatos de build ou exportações automáticas.
✅ Em código legado que ninguém sabe o que vai acontecer depois que for alterado.


## ✍️ FACADOC

Copie e cole no seu código:

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
 * ║  SAIBA MAIS SOBRE O FACADOC: https://git.new/facadoc ║
 * ╚══════════════════════════════════════════════════════╝
 */
```

## 🏆 Veja um caso de uso 10 anos depois

<div>
<video controls src="https://github.com/user-attachments/assets/6c5349b7-8af2-4c5f-a7df-e64297bb8df5">
</video>
</div>



## ⚠️ Regras de Conduta

- **Nunca** edite manualmente arquivos que possuem o FACADOC.  
- Alterações devem ser feitas nos **scripts ou processos** que geram o arquivo.  
- Qualquer alteração direta será sobrescrita ou pode comprometer o sistema.  
- Se identificar um arquivo crítico sem FACADOC, avalie se ele deveria ter.
- Se alterar um código que tenha a FACA, faça por sua conta em risco.



## 🎯 Objetivo

- Reduzir o risco de erros humanos.  
- Facilitar a identificação de arquivos protegidos.  
- Manter a integridade de processos automatizados.  
- Criar um padrão visual simples e efetivo em toda a base de código.
- Avisar desenvolvedores no futuro que vai dar merda.



## 🛡️ Recomendação

Para equipes que geram arquivos automaticamente (configs, manifests, builds, etc.), padronize o uso do **FACADOC**. É simples, visual e altamente eficiente.

