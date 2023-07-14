
.PHONY: watch, clean, tidy

NAME=abstract

$(NAME).pdf: $(NAME).tex 
	latexmk -pdf -f $(NAME).tex 

watch:
	latexmk -pdf -latexoption="-interaction=batchmode" -f -pvc $(NAME).tex 

clean:
	latexmk -pdf -f -C $(NAME).tex 

tidy:
	latexmk -pdf -f -c $(NAME).tex 



