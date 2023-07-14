
.PHONY: watch, clean, tidy

presentatie.pdf: presentatie.tex 
	latexmk -xelatex -f presentatie.tex 

watch:
	latexmk -xelatex -latexoption="-interaction=batchmode" -f -pvc presentatie.tex 

clean:
	latexmk -xelatex -f -C presentatie.tex 

tidy:
	latexmk -xelatex -f -c presentatie.tex 



