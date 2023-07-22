zSRC_DIR := src
OUT_DIR := out
DOC_DIR := doc

JC := javac
JDOC := javadoc
JSRC := -sourcepath ./$(SRC_DIR)
JCLASS := -cp ./$(OUT_DIR)
JCDEST := -d $(OUT_DIR)
JDOCDEST := -d $(DOC_DIR)
MAIN_SOURCE := ru/gb/Main
MAIN_CLASS := ru.gb.Main

all:
    ${JC} ${JSRC} ${JCDEST} ${SRC_DIR}/${MAIN_SOURCE}.java

clean:
    rm -R ${OUT_DIR}

run:
    cd out && java ${MAIN_CLASS}

docs:
    ${JDOC} ${JDOCDEST} ${JSRC} ${JCLASS} -subpackages ru
 vsvars32.bat (c:\Program Files (x86)\Microsoft Visual Studio 9.0\Common7\Tools для VS2008). 