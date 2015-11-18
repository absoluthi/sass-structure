#SASS Structure
Criei o projeto para concentrar a estrutura de pastas para SASS em projetos que eu desenvolvo. A ideia é ter sempre a mesma estrtura e funcionamento para todos os projetos e ainda sim ter uma forma de avançar e divulgar isso.

##Structure:
	my-project/

			assets/

				sass/

					main.scss
					# Import de todos os arquivos do projeto
		
					_config.scss
					# Config do projeto - font-face, font-family, cores, icons, sizes, fórmulas, variáveis e etc.
		
					layout/
					#Aqui eu uso para fazer o layout das minhas páginas, separadamente. A ideia é que seja um arquivo onde eu defino coisas gerais de estrutura na página e alguns itens específicos.
		
						_home.scss
			
						_contact.scss
			
					modules/
					#Vão ser usados para modularizar o projeto, melhorar o uso de código. Ou seja, quando eu tenho um mesmo item que se repete por páginas ou que tem a mesma estrutura, eu defino um módulo pra ele e só faço o uso correto na página de layout.
					#Mixins também são declarados aqui, mas com uma nomenclatura especial: O prefixo `_mx` indica um mixin que pode receber parametros e funcionalidades de acordo com o uso do projeto.
			
						_title.scss
			
						_mx-reset-list.scss
			
						_mx-font-antialised.scss


##To Do:
* How to Use
* Criar mixins padrão (font antialised, reset list,)
* Implementar uso com Bourbon
* Implementar uso com Unsemantic
* Implementar uso com normalize
* Implementar bower trazendo as dependencias acima;
* Implementar grunt/gulp (analisar uso correto)
