
### **Tabela ASCII (0x00 a 0xFF)**
| **Hex** | **Dec** | **Char**  | **Descrição**                     | **Tradução/Descrição (Português)**                     |
|---------|---------|-----------|-----------------------------------|--------------------------------------------------------|
| `00`    | 0       | `NUL`     | Null (Caractere nulo)             | Nulo (Caractere de preenchimento) |
| `01`    | 1       | `SOH`     | Start of Heading                  | Início do Cabeçalho (início de uma mensagem) |
| `02`    | 2       | `STX`     | Start of Text                     | Início do Texto (dados principais) |
| `03`    | 3       | `ETX`     | End of Text                       | Fim do Texto |
| `04`    | 4       | `EOT`     | End of Transmission               | Fim da Transmissão |
| `05`    | 5       | `ENQ`     | Enquiry                           | Consulta ("Você está pronto?") |
| `06`    | 6       | `ACK`     | Acknowledge                       | Confirmação ("Dados recebidos") |
| `07`    | 7       | `BEL`     | Bell (Alarme)                     | Sino (alarme sonoro) |
| `08`    | 8       | `BS`      | Backspace                         | Retrocesso (apaga caractere anterior) |
| `09`    | 9       | `TAB`     | Horizontal Tab                    | Tabulação Horizontal (tecla `Tab`)  |
| `0A`    | 10      | `LF`      | Line Feed (Quebra de linha)       | Alimentação de Linha (quebra de linha Unix) |
| `0B`    | 11      | `VT`      | Vertical Tab                      | Tabulação Vertical |
| `0C`    | 12      | `FF`      | Form Feed (Quebra de página)      | Alimentação de Formulário (nova página) |
| `0D`    | 13      | `CR`      | Carriage Return                   | Retorno de Carro (início da linha, usado com `LF` em Windows) |
| `0E`    | 14      | `SO`      | Shift Out                         | Saída de Shift (ativa caracteres especiais) |
| `0F`    | 15      | `SI`      | Shift In                          | Entrada de Shift (volta ao padrão) |
| `10`    | 16      | `DLE`     | Data Link Escape                  | Escape de Enlace de Dados (controle de protocolo) |
| `11`    | 17      | `DC1`     | Device Control 1                  | Controle de Dispositivo 1 (ex.: ligar impressora) |
| `12`    | 18      | `DC2`     | Device Control 2                  | Controle de Dispositivo 2 |
| `13`    | 19      | `DC3`     | Device Control 3                  | Controle de Dispositivo 3 (ex.: desligar impressora) |
| `14`    | 20      | `DC4`     | Device Control 4                  | Controle de Dispositivo 4 |
| `15`    | 21      | `NAK`     | Negative Acknowledge              | Confirmação Negativa ("Erro na transmissão") |
| `16`    | 22      | `SYN`     | Synchronous Idle                  | Sincronização Inativa (sincroniza comunicação serial) |
| `17`    | 23      | `ETB`     | End of Trans. Block               | Fim do Bloco de Transmissão |
| `18`    | 24      | `CAN`     | Cancel                            | Cancelar (interrompe operação) |
| `19`    | 25      | `EM`      | End of Medium                     | Fim da Mídia (ex.: fim de fita magnética) |
| `1A`    | 26      | `SUB`     | Substitute                        | Substituir (caractere inválido) |
| `1B`    | 27      | `ESC`     | Escape                            | Escape (inicia sequências de controle) |
| `1C`    | 28      | `FS`      | File Separator                    | Separador de Arquivo |
| `1D`    | 29      | `GS`      | Group Separator                   | Separador de Grupo |
| `1E`    | 30      | `RS`      | Record Separator                  | Separador de Registro |
| `1F`    | 31      | `US`      | Unit Separator                    | Separador de Unidade |
| `20`    | 32      | ` `       | Espaço                            | Espaço em branco |
| `21`    | 33      | `!`       | Exclamação                        | |
| `22`    | 34      | `"`       | Aspas duplas                      | |
| `23`    | 35      | `#`       | Cerquilha                         | |
| `24`    | 36      | `$`       | Dólar                             | |
| `25`    | 37      | `%`       | Porcentagem                       | |
| `26`    | 38      | `&`       | E comercial                       | |
| `27`    | 39      | `'`       | Aspas simples                     | |
| `28`    | 40      | `(`       | Parêntese esquerdo                | |
| `29`    | 41      | `)`       | Parêntese direito                 | |
| `2A`    | 42      | `*`       | Asterisco                         | |
| `2B`    | 43      | `+`       | Mais                              | |
| `2C`    | 44      | `,`       | Vírgula                           | |
| `2D`    | 45      | `-`       | Hífen                             | |
| `2E`    | 46      | `.`       | Ponto                             | |
| `2F`    | 47      | `/`       | Barra                             | |
| `30`    | 48      | `0`       | Dígito 0                          | |
| `31`    | 49      | `1`       | Dígito 1                          | |
| `32`    | 50      | `2`       | Dígito 2                          | |
| `33`    | 51      | `3`       | Dígito 3                          | |
| `34`    | 52      | `4`       | Dígito 4                          | |
| `35`    | 53      | `5`       | Dígito 5                          | |
| `36`    | 54      | `6`       | Dígito 6                          | |
| `37`    | 55      | `7`       | Dígito 7                          | |
| `38`    | 56      | `8`       | Dígito 8                          | |
| `39`    | 57      | `9`       | Dígito 9                          | |
| `3A`    | 58      | `:`       | Dois pontos                       | |
| `3B`    | 59      | `;`       | Ponto e vírgula                   | |
| `3C`    | 60      | `<`       | Menor que                         | |
| `3D`    | 61      | `=`       | Igual                             | |
| `3E`    | 62      | `>`       | Maior que                         | |
| `3F`    | 63      | `?`       | Interrogação                      | |
| `40`    | 64      | `@`       | Arroba                            | |
| `41`    | 65      | `A`       | Letra A                           | |
| `42`    | 66      | `B`       | Letra B                           | |
| `43`    | 67      | `C`       | Letra C                           | |
| `44`    | 68      | `D`       | Letra D                           | |
| `45`    | 69      | `E`       | Letra E                           | |
| `46`    | 70      | `F`       | Letra F                           | |
| `47`    | 71      | `G`       | Letra G                           | |
| `48`    | 72      | `H`       | Letra H                           | |
| `49`    | 73      | `I`       | Letra I                           | |
| `4A`    | 74      | `J`       | Letra J                           | |
| `4B`    | 75      | `K`       | Letra K                           | |
| `4C`    | 76      | `L`       | Letra L                           | |
| `4D`    | 77      | `M`       | Letra M                           | |
| `4E`    | 78      | `N`       | Letra N                           | |
| `4F`    | 79      | `O`       | Letra O                           | |
| `50`    | 80      | `P`       | Letra P                           | |
| `51`    | 81      | `Q`       | Letra Q                           | |
| `52`    | 82      | `R`       | Letra R                           | |
| `53`    | 83      | `S`       | Letra S                           | |
| `54`    | 84      | `T`       | Letra T                           | |
| `55`    | 85      | `U`       | Letra U                           | |
| `56`    | 86      | `V`       | Letra V                           | |
| `57`    | 87      | `W`       | Letra W                           | |
| `58`    | 88      | `X`       | Letra X                           | |
| `59`    | 89      | `Y`       | Letra Y                           | |
| `5A`    | 90      | `Z`       | Letra Z                           | |
| `5B`    | 91      | `[`       | Colchete esquerdo                 | |
| `5C`    | 92      | `\`       | Barra invertida                   | |
| `5D`    | 93      | `]`       | Colchete direito                  | |
| `5E`    | 94      | `^`       | Circunflexo                       | |
| `5F`    | 95      | `_`       | Sublinhado                        | |         
| `60`    | 96      | `` ` ``   | Crase                             | |
| `61`    | 97      | `a`       | Letra a                           | |
| `62`    | 98      | `b`       | Letra b                           | |
| `63`    | 99      | `c`       | Letra c                           | |
| `64`    | 100     | `d`       | Letra d                           | |
| `65`    | 101     | `e`       | Letra e                           | |
| `66`    | 102     | `f`       | Letra f                           | |
| `67`    | 103     | `g`       | Letra g                           | |
| `68`    | 104     | `h`       | Letra h                           | |
| `69`    | 105     | `i`       | Letra i                           | |
| `6A`    | 106     | `j`       | Letra j                           | |
| `6B`    | 107     | `k`       | Letra k                           | |
| `6C`    | 108     | `l`       | Letra l                           | |
| `6D`    | 109     | `m`       | Letra m                           | |
| `6E`    | 110     | `n`       | Letra n                           | |
| `6F`    | 111     | `o`       | Letra o                           | |
| `70`    | 112     | `p`       | Letra p                           | |
| `71`    | 113     | `q`       | Letra q                           | |
| `72`    | 114     | `r`       | Letra r                           | |
| `73`    | 115     | `s`       | Letra s                           | |
| `74`    | 116     | `t`       | Letra t                           | |
| `75`    | 117     | `u`       | Letra u                           | |
| `76`    | 118     | `v`       | Letra v                           | |
| `77`    | 119     | `w`       | Letra w                           | |
| `78`    | 120     | `x`       | Letra x                           | |
| `79`    | 121     | `y`       | Letra y                           | |
| `7A`    | 122     | `z`       | Letra z                           | |
| `7B`    | 123     | `{`       | Chave esquerda                    | |
| `7C`    | 124     | `l`       | Barra vertical                    | |
| `7D`    | 125     | `}`       | Chave direita                     | |
| `7E`    | 126     | `~`       | Til                               | |
| `7F`    | 127     | `DEL`     | Delete                            | |
| `80`    | 128     | `€` ou `PAD` | C cedilha maiúscula               | |
| `81`    | 129     | `ü` ou `HOP` | u com trema                       | |
| `82`    | 130     | `‚` ou `BPH` | e agudo                           | |
| `83`    | 131     | `ƒ` ou `NBH` | a circunflexo                     | |
| `84`    | 132     | `„` ou `IND` | a com trema                       | |
| `85`    | 133     | `…` ou `NEL` | a grave                           | |
| `86`    | 134     | `†` ou `SSA` | a com anel                        | |
| `87`    | 135     | `‡` ou `ESA` | c cedilha minúscula               | |
| `88`    | 136     | `ˆ` ou `HTS` | e circunflexo                     | |
| `89`    | 137     | `‰` ou `HTJ` | e com trema                       | |
| `8A`    | 138     | `Š` ou `LTS` | e grave                           | |
| `8B`    | 139     | `‹` ou `PLD` | i com trema                       | |
| `8C`    | 140     | `Œ` ou `PLU` | i circunflexo                     | |
| `8D`    | 141     | `ì` ou `RI`  | i grave                           | |
| `8E`    | 142     | `Ž` ou `SS2` | A com trema                       | |
| `8F`    | 143     | `Å` ou `SS3` | A com anel                        | |
| `90`    | 144     | `É` ou `DCS` | E agudo                           | |
| `91`    | 145     | `‘` ou `PU1` | Ligatura ae                       | |
| `92`    | 146     | `’` ou `PU2` | Ligatura AE                       | |
| `93`    | 147     | `“` ou `STS` | o circunflexo                     | |
| `94`    | 148     | `”` ou `CCH` | o com trema                       | |
| `95`    | 149     | `•` ou `MW`  | o grave                           | |
| `96`    | 150     | `–` ou `SPA` | u circunflexo                     | |
| `97`    | 151     | `—` ou `EPA` | u grave                           | |
| `98`    | 152     | `˜` ou `SOS` | y com trema                       | |
| `99`    | 153     | `™` ou `SGCI` | O com trema                       | |
| `9A`    | 154     | `š` ou `SCI` | U com trema                       | |
| `9B`    | 155     | `›` ou `CSI` | Centavo                           | |
| `9C`    | 156     | `œ` ou `ST`  | Libra esterlina                   | |
| `9D`    | 157     | ` ` ou `OSC` | Yen                               | |
| `9E`    | 158     | `ž` ou `PM`  | Peseta                            | |
| `9F`    | 159     | `Ÿ` ou `APC` | Florim                            | |
| `A0`    | 160     | ` ` ou `NBSP` | a agudo                           | |
| `A1`    | 161     | `¡` ou `Ё` | i agudo                           | |
| `A2`    | 162     | `¢` ou `Ђ` | o agudo                           | |
| `A3`    | 163     | `£` ou `Ѓ` | u agudo                           | |
| `A4`    | 164     | `¤` ou `Є` | n com til                         | |
| `A5`    | 165     | `¥` ou `Ѕ` | N com til                         | |
| `A6`    | 166     | `¦` ou `I` | Ordem feminina                    | |
| `A7`    | 167     | `§` ou `Ї` | Ordem masculina                   | |
| `A8`    | 168     | `¨` ou `J` | Interrogação invertida            | |
| `A9`    | 169     | `©` ou `Љ` | Símbolo gráfico                   | |
| `AA`    | 170     | `ª` ou `Њ` | Negação                           | |
| `AB`    | 171     | `«` ou `Ћ` | Meio                              | |
| `AC`    | 172     | `¬` ou `Ќ` | Um quarto                         | |
| `AD`    | 173     | ` `        | Exclamação invertida              | |
| `AE`    | 174     | `®` ou `Ў` | Aspas angulares esquerda          | |
| `AF`    | 175     | `¯` ou `Џ` | Aspas angulares direita           | |
| `B0`    | 176     | `°` ou `А` | Bloco claro                       | |
| `B1`    | 177     | `±` ou `Б` | Bloco médio                       | |
| `B2`    | 178     | `²` ou `В` | Bloco escuro                      | |
| `B3`    | 179     | `³` ou `Г` | Linha vertical                    | |
| `B4`    | 180     | `´` ou `Д` | Linha vertical + direita          | |
| `B5`    | 181     | `µ` ou `Е` | Linha vertical dupla              | |
| `B6`    | 182     | `¶` ou `Ж` | Linha vertical dupla + direita    | |
| `B7`    | 183     | `·` ou `З` | Canto superior esquerdo           | |
| `B8`    | 184     | `¸` ou `И` | Canto superior direito            | |
| `B9`    | 185     | `¹` ou `Й` | Linha vertical dupla + esquerda   | |
| `BA`    | 186     | `º` ou `К` | Linha vertical dupla              | |
| `BB`    | 187     | `»` ou `Л` | Canto inferior direito            | |
| `BC`    | 188     | `¼` ou `М` | Canto inferior esquerdo           | |
| `BD`    | 189     | `½` ou `Н` | Canto inferior esquerdo duplo     | |
| `BE`    | 190     | `¾` ou `О` | Canto inferior direito duplo      | |
| `BF`    | 191     | `¿` ou `П` | Canto superior direito            | |
| `C0`    | 192     | `À` ou `P` | Canto inferior esquerdo           | |
| `C1`    | 193     | `Á` ou `C` | Linha horizontal inferior         | |
| `C2`    | 194     | `Â` ou `T` | Linha horizontal superior         | |
| `C3`    | 195     | `Ã` ou `y` | Linha vertical + esquerda         | |
| `C4`    | 196     | `Ä` ou `Ф` | Linha horizontal                  | |
| `C5`    | 197     | `Å` ou `X` | Cruz                              | |
| `C6`    | 198     | `Æ` ou `Ц` | Linha vertical dupla + esquerda   | |
| `C7`    | 199     | `Ç` ou `Ч` | Linha vertical dupla + direita    | |
| `C8`    | 200     | `È` ou `Ш` | Canto inferior esquerdo duplo     | |
| `C9`    | 201     | `É` ou `Щ` | Canto superior esquerdo duplo     | |
| `CA`    | 202     | `Ê` ou `Ъ` | Linha horizontal inferior dupla   | |
| `CB`    | 203     | `Ë` ou `Ы` | Linha horizontal superior dupla   | |
| `CC`    | 204     | `Ì` ou `Ь` | Linha vertical dupla + esquerda   | |
| `CD`    | 205     | `Í` ou `Э` | Linha horizontal dupla            | |
| `CE`    | 206     | `Î` ou `Ю` | Cruz dupla                        | |
| `CF`    | 207     | `Ï` ou `Я` | Linha horizontal inferior dupla   | |
| `D0`    | 208     | `Ð` ou `а` | Linha horizontal inferior dupla   | |
| `D1`    | 209     | `Ñ` ou `б` | Linha horizontal superior dupla   | |
| `D2`    | 210     | `Ò` ou `в` | Linha horizontal superior dupla   | |
| `D3`    | 211     | `Ó` ou `г` | Canto inferior direito duplo      | |
| `D4`    | 212     | `Ô` ou `д` | Canto inferior esquerdo duplo     | |
| `D5`    | 213     | `Õ` ou `е` | Canto superior esquerdo duplo     | |
| `D6`    | 214     | `Ö` ou `ж` | Canto superior direito duplo      | |
| `D7`    | 215     | `×` ou `з` | Cruz dupla                        | |
| `D8`    | 216     | `Ø` ou `и` | Cruz dupla                        | |
| `D9`    | 217     | `Ù` ou `й` | Canto inferior direito            | |
| `DA`    | 218     | `Ú` ou `к` | Canto superior esquerdo           | |
| `DB`    | 219     | `Û` ou `л` | Bloco sólido                      | |
| `DC`    | 220     | `Ü` ou `м` | Metade inferior do bloco          | |
| `DD`    | 221     | `Ý` ou `н` | Metade esquerda do bloco          | |
| `DE`    | 222     | `Þ` ou `о` | Metade direita do bloco           | |
| `DF`    | 223     | `ß` ou `п` | Metade superior do bloco          | |
| `E0`    | 224     | `à` ou `р` | Letra grega alfa                  | |
| `E1`    | 225     | `á` ou `с` | Letra alemã beta                  | |
| `E2`    | 226     | `â` ou `т` | Letra grega gama                  | |
| `E3`    | 227     | `ã` ou `у` | Letra grega pi                    | |
| `E4`    | 228     | `ä` ou `ф` | Letra grega sigma                 | |
| `E5`    | 229     | `å` ou `х` | Letra grega sigma minúscula       | |
| `E6`    | 230     | `æ` ou `ц` | Micro                             | |
| `E7`    | 231     | `ç` ou `ч` | Letra grega tau                   | |
| `E8`    | 232     | `è` ou `ш` | Letra grega phi                   | |
| `E9`    | 233     | `é` ou `щ` | Letra grega theta                 | |
| `EA`    | 234     | `ê` ou `ъ` | Letra grega omega                 | |
| `EB`    | 235     | `ë` ou `ы` | Letra grega delta                 | |
| `EC`    | 236     | `ì` ou `ь` | Infinito                          | |
| `ED`    | 237     | `í` ou `э` | Letra grega phi minúscula         | |
| `EE`    | 238     | `î` ou `ю` | Letra grega epsilon               | |
| `EF`    | 239     | `ï` ou `я` | Interseção                        | |
| `F0`    | 240     | `ð` ou `№` | Equivalente                       | |
| `F1`    | 241     | `ñ` ou `ё` | Mais ou menos                     | | 
| `F2`    | 242     | `ò` ou `ђ` | Maior ou igual                    | | 
| `F3`    | 243     | `ó` ou `ѓ` | Menor ou igual                    | | 
| `F4`    | 244     | `ô` ou `є` | Integral superior                 | |
| `F5`    | 245     | `õ` ou `ѕ` | Integral inferior                 | |
| `F6`    | 246     | `ö` ou `і` | Divisão                           | |
| `F7`    | 247     | `÷` ou `ї` | Aproximadamente                   | |
| `F8`    | 248     | `ø` ou `ј` | Grau                              | |
| `F9`    | 249     | `ù` ou `љ` | Ponto de operação                 | |
| `FA`    | 250     | `ú` ou `њ` | Ponto central                     | |
| `FB`    | 251     | `û` ou `ћ` | Raiz quadrada                     | |
| `FC`    | 252     | `ü` ou `ќ` | Expoente n                        | |
| `FD`    | 253     | `ý` ou `§` | Expoente 2                        | |
| `FE`    | 254     | `þ` ou `ў` | Quadrado preto                    | |
| `FF`    | 255     | `ÿ` ou `џ` | Espaço sem quebra                 | |


| HEX     | LETRAS COM ACENTUAÇÕES | DESCRIÇÃO |
|---------|---------|---------|
| `C0 80` | `P` | |
| `C1 B0` |
| `C2 A0` | ` `     | espaço inquebrável |
| `C3 80` | `À`     | letra `À` maiúsculo com acento grave |
| `C3 81` | `Á`     | letra `Á` maiúsculo com acento agudo |
| `C3 82` | `Â`     | letra `Â` maiúsculo com acento circunflexo |
| `C3 83` | `Ã`     | letra `Ã` maiúsculo com acento til |
| `C3 84` | `Ä`     | |
| `C3 85` | `Å`     | |
| `C3 86` | `Æ`     | |
| `C3 87` | `Ç`     | letra `Ç` maiúsculo com acento C cedilha |
| `C3 88` | `È`     | letra `È` maiúsculo com acento grave |
| `C3 89` | `É`     | letra `É` maiúsculo com acento agudo |
| `C3 8A` | `Ê`     | letra `Ê` maiúsculo com acento circunflexo |
| `C3 8B` | `Ë`     | |
| `C3 8C` | `Ì`     | letra `Ì` maiúsculo com acento grave |
| `C3 8D` | `Í`     | letra `Í` maiúsculo com acento agudo |
| `C3 8E` | `Î`     | letra `Î` maiúsculo com acento circunflexo |
| `C3 8F` | `Ï`     | |
| `C3 90` | `Ð`     | |
| `C3 91` | `Ñ`     | |
| `C3 92` | `Ò`     | letra `Ò` maiúsculo com acento grave |
| `C3 93` | `Ó`     | letra `Ó` maiúsculo com acento agudo |
| `C3 94` | `Ô`     | letra `Ô` maiúsculo com acento circunflexo |
| `C3 95` | `Õ`     | letra `Õ` maiúsculo com acento til |
| `C3 96` | `Ö`     | |
| `C3 97` | `×`     | |
| `C3 98` | `Ø`     | |
| `C3 99` | `Ù`     | letra `Ù` maiúsculo com acento grave |
| `C3 9A` | `Ú`     | letra `Ú` maiúsculo com acento agudo |
| `C3 9B` | `Û`     | letra `Û` maiúsculo com acento circunflexo |
| `C3 9C` | `Ü`     | |
| `C3 9D` | `Ý`     | |
| `C3 9E` | `Þ`     | |
| `C3 9F` | `ß`     | |
| `C3 A0` | `à`     | letra `à` minúsculo com acento grave | 
| `C3 A1` | `á`     | letra `á` minúsculo com acento agudo |
| `C3 A2` | `â`     | letra `â` minúsculo com acento circunflexo |
| `C3 A3` | `ã`     | letra `ã` minúsculo com acento til |
| `C3 A4` | `ä`     | |
| `C3 A5` | `å`     | | 
| `C3 A6` | `æ`     | |
| `C3 A7` | `ç`     | |
| `C3 A8` | `è`     | letra `è` minúsculo com acento grave |
| `C3 A9` | `é`     | letra `é` minúsculo com acento agudo |
| `C3 AA` | `ê`     | letra `ê` minúsculo com acento circunflexo |
| `C3 AB` | `ë`     | |
| `C3 AC` | `ì`     | letra `ì` minúsculo com acento grave |
| `C3 AD` | `í`     | letra `í` minúsculo com acento agudo |
| `C3 AE` | `î`     | letra `î` minúsculo com acento circunflexo |
| `C3 AF` | `ï`     | |
| `C3 B0` | `ð`     | |
| `C3 B1` | `ñ`     | |
| `C3 B2` | `ò`     | letra `ò` minúsculo com acento grave |
| `C3 B3` | `ó`     | letra `ó` minúsculo com acento agudo |
| `C3 B4` | `ô`     | letra `ô` minúsculo com acento circunflexo |
| `C3 B5` | `õ`     | letra `õ` minúsculo com acento til |
| `C3 B6` | `ö`     | |
| `C3 B7` | `÷`     | | 
| `C3 B8` | `ø`     | |
| `C3 B9` | `ù`     | letra `ù` minúsculo com acento grave |
| `C3 BA` | `ú`     | letra `ú` minúsculo com acento agudo |
| `C3 BB` | `û`     | letra `û` minúsculo com acento circunflexo |
| `C3 BC` | `ü`     | |
| `C3 BD` | `ý`     | |
| `C3 BE` | `þ`     | |
| `C3 BF` | `ÿ`     | | 
| `C4 80` | `Ā`     | |
| `C4 81` | `ā`     | | 
| `C4 82` | `Ă`     | |
| `C4 83` | `ă`     | |
| `C4 84` | `Ą`     | |
| `C4 85` | `ą`     | |
| `C4 86` | `Ć`     | |
| `C4 87` | `ć`     | |
| `C4 88` | `Ĉ`     | |
| `C4 89` | `ĉ`     | |
| `C4 8A` | `Ċ`     | |
| `C4 8B` | `ċ`     | |
| `C4 8C` | `Č`     | |
| `C4 8D` | `č`     | |
| `C4 8E` | `Ď`     | |
| `C4 8F` | `ď`     | |

## 2 BYTES
| HEX     | INÍCIO  | FIM     |
|---------|---------|---------|
| `C0 80` | `C0 80` | `DF BF` |

## 3 BYTES
| HEX        | INÍCIO     | FIM        |
|------------|------------|------------|
| `E0 80 80` | `E0 80 80` | `EF BF BF` |

## 4 BYTES
| HEX           | INÍCIO        | FIM           |
|---------------|---------------|---------------|
| `F0 80 80 80` | `F0 80 80 80` | `F7 BF BF BF` |


Vamos explorar como o UTF-8 organiza os bytes para representar caracteres Unicode. O UTF-8 usa um esquema de prefixos para indicar quantos bytes formam um caractere. Aqui está um resumo:
### Estrutura Básica do UTF-8:
| Intervalo Unicode       | Bytes no UTF-8      | Padrão do Byte Líder | Bytes Seguintes       |
|-------------------------|---------------------|----------------------|-----------------------|
| U+0000 a U+007F         | 1 byte             | `0xxxxxxx`           | —                    |
| U+0080 a U+07FF         | 2 bytes            | `110xxxxx`           | `10xxxxxx`           |
| U+0800 a U+FFFF         | 3 bytes            | `1110xxxx`           | `10xxxxxx` `10xxxxxx` |
| U+10000 a U+10FFFF      | 4 bytes            | `11110xxx`           | `10xxxxxx` (3 vezes) |
---
### Exemplos de Combinações Válidas:
#### 1. **Caracteres de 1 Byte (ASCII):**
   - São bytes que começam com `0` em binário.
   - **Intervalo Hex:** `00` a `7F`.
   - Exemplos:
     - `41` = `A` (maiúsculo).
     - `24` = `$` (cifrão).
#### 2. **Caracteres de 2 Bytes:**
   - **Byte líder:** Inicia com `110` em binário → Hex `C0` a `DF`.
   - **Byte seguinte:** Inicia com `10` em binário → Hex `80` a `BF`.
   - **Exemplos:**
     - `C3 89` = **É** (E agudo maiúsculo, U+00C9).
     - `C2 A3` = **£** (libra esterlina, U+00A3).
     - `C3 A9` = **é** (e agudo minúsculo, U+00E9).
     - 
#### 3. **Caracteres de 3 Bytes:**
   - **Byte líder:** Inicia com `1110` → Hex `E0` a `EF`.
   - **Bytes seguintes:** Dois bytes do tipo `10xxxxxx` (`80` a `BF`).
   - **Exemplos:**
     - `E2 82 AC` = **€** (euro, U+20AC).
     - `E0 A4 B9` = **ह** (devaganari, U+0939).
     - `EF BB BF` = **BOM** (Byte Order Mark, U+FEFF).
     - 
#### 4. **Caracteres de 4 Bytes:**
   - **Byte líder:** Inicia com `11110` → Hex `F0` a `F7`.
   - **Bytes seguintes:** Três bytes do tipo `10xxxxxx` (`80` a `BF`).
   - **Exemplos:**
     - `F0 9F 98 80` = **😀** (emoji sorridente, U+1F600).
     - `F0 9F A6 96` = **🦖** (T-Rex, U+1F996).
---
### Padrões Inválidos em UTF-8:
Algumas sequências são **proibidas**:
- **Bytes seguidores isolados:** Qualquer byte `80`–`BF` sem um byte líder antes.
- **Bytes líderes incompletos:** Exemplo: `C0` sozinho (deveria ter um byte seguidor).
- **Sobre-longas:** Representar um caractere ASCII (ex: `A`) com 2 bytes (`C1 81` é inválido; o correto é `41`).
- **Intervalos Unicode não atribuídos:** Ex: `ED A0 80` (tentativa de representar U+D800, reservado para surrogate pairs).
---
### Tabela de Referência Rápida:
| Tipo          | Byte Líder (Hex) | Bytes Seguintes (Hex) | Exemplo (Hex → Caractere)        |
|---------------|------------------|----------------------|----------------------------------|
| **1 byte**    | `00`–`7F`        | —                    | `24` = `$`                       |
| **2 bytes**   | `C2`–`DF`        | `80`–`BF`            | `C2 A9` = `©`                    |
| **3 bytes**   | `E0`–`EF`        | `80`–`BF` (×2)       | `E2 99 A5` = `♥`                 |
| **4 bytes**   | `F0`–`F7`        | `80`–`BF` (×3)       | `F0 9F 8C 88` = `🌈`             |
---
### Detecção Prática:
Para identificar se uma sequência hex é UTF-8 válida:
1. Verifique se o primeiro byte está em um intervalo de byte líder (`C0–DF`, `E0–EF`, `F0–F7`).
2. Confirme se os próximos bytes são seguidores (`80–BF`), na quantidade esperada.
Exemplo:  
- `E2 82 AC` → Válido (3 bytes: líder `E2` + dois seguidores `82` e `AC`).  
- `C2 41` → Inválido (`41` não é seguidor, pois está fora de `80-BF`).

### **Observações Importantes**:
1. **ASCII Padrão (0x00–0x7F)**:
   - Contém **caracteres de controle** (não imprimíveis) e **caracteres imprimíveis** básicos.
   - Exemplo: `0x41` = `A`, `0x0A` = `LF` (quebra de linha).

2. **ASCII Estendido (0x80–0xFF)**:
   - Varia conforme a codificação (ISO-8859-1, Windows-1252, etc.).
   - Inclui caracteres acentuados, símbolos e gráficos.

3. **Caracteres de Controle**:
   - `0x00` a `0x1F` e `0x7F` são não imprimíveis (ex.: `0x07` = `BEL` faz o computador bipar).

4. **UTF-8 vs ASCII**:
   - Caracteres acima de `0x7F` podem ser parte de sequências multibyte em UTF-8.

---

### **Como Usar Esta Tabela**:
- **Para converter hex para char**: Use a coluna **Char** (ex.: `0x48` = `H`).
- **Para debuggar binários**: Identifique caracteres não imprimíveis (ex.: `0x1A` = `SUB`).
- **Em programação**: Use a tabela para codificar/decodificar manualmente.
