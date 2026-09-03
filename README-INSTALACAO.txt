J LUVAN MASTER PRO — V3.2 (correção completa)

O QUE FOI CORRIGIDO NESTA VERSÃO
1. Os filtros "Em progresso", "Concluídos" e "Favoritos" no Curso MASTER não tinham
   nenhuma ação ligada — agora filtram corretamente a lista de módulos.
2. O sistema offline foi reforçado: a partir de agora, quando publicar uma
   atualização no GitHub, o app deteta a nova versão sozinho e atualiza-se
   automaticamente (sem precisar de limpar dados do Safari todas as vezes).
   Isto só vale a partir desta publicação em diante — é preciso fazer UMA
   última limpeza manual para o iPhone largar a versão presa (passo 8 abaixo).

PUBLICAR NO GITHUB PAGES
1. Descompacte este ZIP.
2. No repositório jluvan-master, escolha Add file > Upload files.
3. Envie TODO o conteúdo desta pasta (incluindo a subpasta assets) para a
   RAIZ do repositório.
4. Confirme que index.html fica diretamente na raiz, ao lado de manifest.json
   e sw.js — nunca dentro de outra pasta.
5. Quando o GitHub perguntar, confirme a substituição dos ficheiros existentes.
6. Desça até ao fim da página e toque em Commit changes.
7. Aguarde 1–3 minutos para o GitHub Pages publicar.
8. ÚLTIMA LIMPEZA MANUAL (só desta vez): no iPhone, feche o app instalado,
   depois vá a Definições > Safari > Avançado > Dados de Sites, procure
   jbantuuu-droid.github.io e apague os dados desse site. Isto remove apenas
   progresso, notas, favoritos e preços editados guardados neste dispositivo.
9. Abra novamente https://jbantuuu-droid.github.io/-jluvan-master/ no Safari
   e confirme que os filtros e os separadores ENTENDER/EXECUTAR/FISCALIZAR/
   PRATICAR funcionam.
10. Para instalar: Safari > Partilhar > Adicionar ao Ecrã Principal.

DAQUI PARA A FRENTE
- Sempre que publicar uma nova atualização no GitHub, basta abrir o app com
  internet uma vez: ele vai detetar, transferir e recarregar-se sozinho.
  Já não é preciso repetir a limpeza de dados do Safari.

NOTAS
- O app funciona sem dependências externas e guarda progresso, notas,
  checklist e preços apenas no navegador deste dispositivo.
- Cálculos são apoio de estudo e estimativa. Obras exigem projeto, normas
  aplicáveis, dados de campo e validação por profissional habilitado.
