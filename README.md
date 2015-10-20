#SASS Structure
Criei o projeto para concentrar a estrutura de pastas para SASS em projetos que eu desenvolvo. A ideia é ter sempre a mesma estrtura e funcionamento para todos os projetos e ainda sim ter uma forma de avançar e divulgar isso.

##Structure:
my-project/

		assets/

			sass/

				style.scss # Import de todos os arquivos do projeto
		
				_config.scss
				> Config do projeto - font-face, font-family, cores, icons, sizes, fórmulas, variáveis e etc.
		
				layout/
		
					_home.scss
		
					_contact.scss
		
				modules/
		
					_title.scss
		
					_mx-reset-list.scss
		
					_mx-font-antialised.scss


##To Do:
* How to Use
* Implementar Borbon
* Implementar Unsemantic
* Implementar normalize
* Implementar bower
* Implementar grunt/gulp
