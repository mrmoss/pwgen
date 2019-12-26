# Password Generator

A simple cli utility to make semi-readable temporary passwords.
Made quickly...probably terrible and already exists...but it makes passwords...I guess?

    # ./pwgen -h
    usage: pwgen [-h] [-n N] [-s CHARS] [-w N] DICTPATH [DICTPATH ...]

    Creates passwords

    positional arguments:
      DICTPATH              Path(s) to a newline separated dictionary

    optional arguments:
      -h, --help            show this help message and exit
      -n N, --num-passwords N
                            Number of passwords to generate - default: 1
      -s CHARS, --separators CHARS
                            Characters used for separators - default: !"#$%&'( )*+,-./0123456789:;<=>?@[\]^_`{|}~
      -w N, --num-words N   Number of words to use - default: 4

## Example Usage

    # ./pwgen -n 10 -w 6 /usr/share/dict/
    1auditors-barfliesAZZUFFAIcessasse{zygosporicAUTORIZZAI+
    #THALLUS-UNTRAVELABLE/Firbolg0Gurnetty%sclerized<NILOT
    MAGNETOBELLmoninoSUBERINIZE#AWNINGS*spoucher*INCHINAVA}
    <SLIDINGLY#FisioterapSballati@Eburnated-PARNELLmiscreancy
    8groveless<CLAVATELY\Sapremmo|anovesical}cuspid(derogation$
    <equivali#multiphase2PARSONDOM-Inspirant%MATTINGLY]GLOOMFUL
    7PETCOCK,WARMABLEagonium'muciparous@suprafineSulfate%
    ?SPAVENTAVA}Dentiloquy3coabitate~homelikeOssianCOVERA:
    [Jung_FOLGERITEsuperessentially%cookshackAristotelismHEATHENESSE1
    SPLUTHER9Praecornu]desacralizationCONTROVERTIST{VESTISTE-styliferous#
