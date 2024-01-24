# branch-testing
🌿 Just a branch testing for Git repository.

# Conceitos

## Splash Merge

É a técnica para fazer com que seus últimos _commits_ fiquem após o último _commit_ feito na _branch_ principal. Assim, o Git simplesmente pega seus últimso _commits_ da _branch_ atual, junta tudo em um único _commit_ e coloca após a principal.

> Isso faz com que todo o conteúdo seja reunido em um único commit, contudo a história de todos os novos _commits_ feitos naquela _branch_ são perdidos.

## Merge Rebase

Pega todo o conteúdo que foi feito até então na principal, e coloca antes do primeiro commit que foi feito na branch nova. Por isso `rebase`, já que refaz a estrutura base que foi usada para os commits até então.

Sendo assim, não é uma linha do tempo que é juntada em outra, e sim uuma lkinha do tempo que é integrada em outra que já foi atualizada (principal).

# Resumo

Merge mantém várias linhas paralelas, juntando sempre na principal em algum ponto. Rebase mantém todas as linhas paralelas unificadas na principal.
