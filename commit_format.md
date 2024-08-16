# Formatação dos commits
Cada commit deve possuir um cabeçalho, um corpo e um rodapé.

O cabeçalho tem um formato diferente que inclui o tipo e o assunto do commit.
```
<tipo>: <assunto>
<LINHA EM BRANCO>
<corpo>
<LINHA EM BRANCO>
<rodapé>
Nenhuma linha do commit deve ser maior que 100 caractéres. Isso facilita a visualização no GitHub, 
assim como em outras ferramentas que integram o Git.
```
Tipo
Deve ser um desses:
```
feat: Uma nova funcionalidade
fix: Uma correção de bug
docs: Mudanças unicamente na documentação
deletion: Remoção de arquivos do projeto
refactor: Uma mudança de código que não adiciona funcionalidades nem corrige nenhum bug
perf: Uma mudança que melhora o desempenho
test: Adiciona novos testes ou corrige os ja existentes
green: Novos testes estão passando e sem bugs.
build: Mudanças no processo de instalação ou em ferramentas e libs auxiliares
wip: Continuação do desenvolvimento de uma funcionalidade
style: Mudanças relativas à aparência do projeto
new version: Nova versão completamente implementada
deploy: Commits relacionados ao deploy da aplicação
```
Cada tipo tem seu emoji na frente sendo eles, respectivamente:
```
🏗️ :building_construction: feat
⚙️ :gear: fix
📄 :page_facing_up: docs
🗑️ :wastebasket: deletion
♻️ :recycle: refactor
📈 :chart_with_upwards_trend: perf
📐 :triangular_ruler: test
✅ :white_check_mark: green
🔨 :hammer: build
🚧 :construction: wip
🎨 :art: style
🎉 :tada: new version
🚀 :rocket: deploy
```
Assunto
O assunto contém uma rápida descrição do que foi feito:

Sempre no passado: alterado, incluído, adicionado
primeira letra não deve ser maiúscula
não colocar ponto no final da frase
Corpo
Como no assunto, use o passado. Escreva a motivação da implementação ou mudança feita.
