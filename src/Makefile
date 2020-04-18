OUT = ../bin

all: curriculum relocalizacion

curriculum:
	@printf "\033[1;33m-> \033[34mCompilando\033[0m \"%s.pdf\"...\n" \
	        "Atanasio Rubio Gil - CV"
	@xelatex "cv.tex" > /dev/null
	@xelatex "cv.tex" > /dev/null

relocalizacion:
	@printf "\033[1;33m-> \033[33mRelocalizando fichero de salida\033[0m...\n"
	@mv "cv.pdf" $(OUT)/"Atanasio Rubio Gil - CV.pdf"
