
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
| `80`    | 128     | `€`       | C cedilha maiúscula               | |
| `81`    | 129     | `ü`       | u com trema                       | |
| `82`    | 130     | `‚`       | e agudo                           | |
| `83`    | 131     | `ƒ`       | a circunflexo                     | |
| `84`    | 132     | `„`       | a com trema                       | |
| `85`    | 133     | `…`       | a grave                           | |
| `86`    | 134     | `†`       | a com anel                        | |
| `87`    | 135     | `‡`       | c cedilha minúscula               | |
| `88`    | 136     | `ˆ`       | e circunflexo                     | |
| `89`    | 137     | `‰`       | e com trema                       | |
| `8A`    | 138     | `Š`       | e grave                           | |
| `8B`    | 139     | `‹`       | i com trema                       | |
| `8C`    | 140     | `Œ`       | i circunflexo                     | |
| `8D`    | 141     | `ì`       | i grave                           | |
| `8E`    | 142     | `Ž`       | A com trema                       | |
| `8F`    | 143     | `Å`       | A com anel                        | |
| `90`    | 144     | `É`       | E agudo                           | |
| `91`    | 145     | `‘`       | Ligatura ae                       | |
| `92`    | 146     | `’`       | Ligatura AE                       | |
| `93`    | 147     | `“`       | o circunflexo                     | |
| `94`    | 148     | `”`       | o com trema                       | |
| `95`    | 149     | `•`       | o grave                           | |
| `96`    | 150     | `–`       | u circunflexo                     | |
| `97`    | 151     | `—`       | u grave                           | |
| `98`    | 152     | `˜`       | y com trema                       | |
| `99`    | 153     | `™`       | O com trema                       | |
| `9A`    | 154     | `š`       | U com trema                       | |
| `9B`    | 155     | `›`       | Centavo                           | |
| `9C`    | 156     | `œ`       | Libra esterlina                   | |
| `9D`    | 157     | ` `       | Yen                               | |
| `9E`    | 158     | `ž`       | Peseta                            | |
| `9F`    | 159     | `Ÿ`       | Florim                            | |
| `A0`    | 160     | ` `       | a agudo                           | |
| `A1`    | 161     | `¡`       | i agudo                           | |
| `A2`    | 162     | `¢`       | o agudo                           | |
| `A3`    | 163     | `£`       | u agudo                           | |
| `A4`    | 164     | `¤`       | n com til                         | |
| `A5`    | 165     | `¥`       | N com til                         | |
| `A6`    | 166     | `¦`       | Ordem feminina                    | |
| `A7`    | 167     | `§`       | Ordem masculina                   | |
| `A8`    | 168     | `¨`       | Interrogação invertida            | |
| `A9`    | 169     | `©`       | Símbolo gráfico                   | |
| `AA`    | 170     | `ª`       | Negação                           | |
| `AB`    | 171     | `«`       | Meio                              | |
| `AC`    | 172     | `¬`       | Um quarto                         | |
| `AD`    | 173     | ` `       | Exclamação invertida              | |
| `AE`    | 174     | `®`       | Aspas angulares esquerda          | |
| `AF`    | 175     | `¯`       | Aspas angulares direita           | |
| `B0`    | 176     | `°`       | Bloco claro                       | |
| `B1`    | 177     | `±`       | Bloco médio                       | |
| `B2`    | 178     | `²`       | Bloco escuro                      | |
| `B3`    | 179     | `³`       | Linha vertical                    | |
| `B4`    | 180     | `´`       | Linha vertical + direita          | |
| `B5`    | 181     | `µ`       | Linha vertical dupla              | |
| `B6`    | 182     | `¶`       | Linha vertical dupla + direita    | |
| `B7`    | 183     | `·`       | Canto superior esquerdo           | |
| `B8`    | 184     | `¸`       | Canto superior direito            | |
| `B9`    | 185     | `¹`       | Linha vertical dupla + esquerda   | |
| `BA`    | 186     | `º`       | Linha vertical dupla              | |
| `BB`    | 187     | `»`       | Canto inferior direito            | |
| `BC`    | 188     | `¼`       | Canto inferior esquerdo           | |
| `BD`    | 189     | `½`       | Canto inferior esquerdo duplo     | |
| `BE`    | 190     | `¾`       | Canto inferior direito duplo      | |
| `BF`    | 191     | `¿`       | Canto superior direito            | |
| `C0`    | 192     | `À`       | Canto inferior esquerdo           | |
| `C1`    | 193     | `Á`       | Linha horizontal inferior         | |
| `C2`    | 194     | `Â`       | Linha horizontal superior         | |
| `C3`    | 195     | `Ã`       | Linha vertical + esquerda         | |
| `C4`    | 196     | `Ä`       | Linha horizontal                  | |
| `C5`    | 197     | `Å`       | Cruz                              | |
| `C6`    | 198     | `Æ`       | Linha vertical dupla + esquerda   | |
| `C7`    | 199     | `Ç`       | Linha vertical dupla + direita    | |
| `C8`    | 200     | `È`       | Canto inferior esquerdo duplo     | |
| `C9`    | 201     | `É`       | Canto superior esquerdo duplo     | |
| `CA`    | 202     | `Ê`       | Linha horizontal inferior dupla   | |
| `CB`    | 203     | `Ë`       | Linha horizontal superior dupla   | |
| `CC`    | 204     | `Ì`       | Linha vertical dupla + esquerda   | |
| `CD`    | 205     | `Í`       | Linha horizontal dupla            | |
| `CE`    | 206     | `Î`       | Cruz dupla                        | |
| `CF`    | 207     | `Ï`       | Linha horizontal inferior dupla   | |
| `D0`    | 208     | `Ð`       | Linha horizontal inferior dupla   | |
| `D1`    | 209     | `Ñ`       | Linha horizontal superior dupla   | |
| `D2`    | 210     | `Ò`       | Linha horizontal superior dupla   | |
| `D3`    | 211     | `Ó`       | Canto inferior direito duplo      | |
| `D4`    | 212     | `Ô`       | Canto inferior esquerdo duplo     | |
| `D5`    | 213     | `Õ`       | Canto superior esquerdo duplo     | |
| `D6`    | 214     | `Ö`       | Canto superior direito duplo      | |
| `D7`    | 215     | `×`       | Cruz dupla                        | |
| `D8`    | 216     | `Ø`       | Cruz dupla                        | |
| `D9`    | 217     | `Ù`       | Canto inferior direito            | |
| `DA`    | 218     | `Ú`       | Canto superior esquerdo           | |
| `DB`    | 219     | `Û`       | Bloco sólido                      | |
| `DC`    | 220     | `Ü`       | Metade inferior do bloco          | |
| `DD`    | 221     | `Ý`       | Metade esquerda do bloco          | |
| `DE`    | 222     | `Þ`       | Metade direita do bloco           | |
| `DF`    | 223     | `ß`       | Metade superior do bloco          | |
| `E0`    | 224     | `à`       | Letra grega alfa                  | |
| `E1`    | 225     | `á`       | Letra alemã beta                  | |
| `E2`    | 226     | `â`       | Letra grega gama                  | |
| `E3`    | 227     | `ã`       | Letra grega pi                    | |
| `E4`    | 228     | `ä`       | Letra grega sigma                 | |
| `E5`    | 229     | `å`       | Letra grega sigma minúscula       | |
| `E6`    | 230     | `æ`       | Micro                             | |
| `E7`    | 231     | `ç`       | Letra grega tau                   | |
| `E8`    | 232     | `è`       | Letra grega phi                   | |
| `E9`    | 233     | `é`       | Letra grega theta                 | |
| `EA`    | 234     | `ê`       | Letra grega omega                 | |
| `EB`    | 235     | `ë`       | Letra grega delta                 | |
| `EC`    | 236     | `ì`       | Infinito                          | |
| `ED`    | 237     | `í`       | Letra grega phi minúscula         | |
| `EE`    | 238     | `î`       | Letra grega epsilon               | |
| `EF`    | 239     | `ï`       | Interseção                        | |
| `F0`    | 240     | `ð`       | Equivalente                       | |
| `F1`    | 241     | `ñ`       | Mais ou menos                     | | 
| `F2`    | 242     | `ò`       | Maior ou igual                    | | 
| `F3`    | 243     | `ó`       | Menor ou igual                    | | 
| `F4`    | 244     | `ô`       | Integral superior                 | |
| `F5`    | 245     | `õ`       | Integral inferior                 | |
| `F6`    | 246     | `ö`       | Divisão                           | |
| `F7`    | 247     | `÷`       | Aproximadamente                   | |
| `F8`    | 248     | `ø`       | Grau                              | |
| `F9`    | 249     | `ù`       | Ponto de operação                 | |
| `FA`    | 250     | `ú`       | Ponto central                     | |
| `FB`    | 251     | `û`       | Raiz quadrada                     | |
| `FC`    | 252     | `ü`       | Expoente n                        | |
| `FD`    | 253     | `ý`       | Expoente 2                        | |
| `FE`    | 254     | `þ`       | Quadrado preto                    | |
| `FF`    | 255     | `ÿ`       | Espaço sem quebra                 | |

| HEX     | LETRAS COM ACENTUAÇÕES | DESCRIÇÃO |
|---------|---------|---------|
| `C3 A0` | `à`     | letra `à` minúsculo com acento grave | 
| `C3 A1` | `á`     | letra `á` minúsculo com acento agudo |
| `C3 A2` | `â`     | letra `â` minúsculo com acento circunflexo |
| `C3 A3` | `ã`     | letra `ã` minúsculo com acento til |
| `C3 A8` | `è`     | letra `è` minúsculo com acento grave |
| `C3 A9` | `é`     | letra `é` minúsculo com acento agudo |
| `C3 AA` | `ê`     | letra `ê` minúsculo com acento circunflexo |
| `C3 AC` | `ì`     | letra `ì` minúsculo com acento grave |
| `C3 AD` | `í`     | letra `í` minúsculo com acento agudo |
| `C3 AE` | `î`     | letra `î` minúsculo com acento circunflexo |
| `C3 B2` | `ò`     | letra `ò` minúsculo com acento grave |
| `C3 B3` | `ó`     | letra `ó` minúsculo com acento agudo |
| `C3 B4` | `ô`     | letra `ô` minúsculo com acento circunflexo |
| `C3 B5` | `õ`     | letra `õ` minúsculo com acento til |
| `C3 B9` | `ù`     | letra `ù` minúsculo com acento grave |
| `C3 BA` | `ú`     | letra `ú` minúsculo com acento agudo |
| `C3 BB` | `û`     | letra `û` minúsculo com acento circunflexo |
| `C3 A7` | `ç`     | letra `ç` minúsculo com c cedilha |
| `C3 80` | `À`     | letra `À` maiúsculo com acento grave |
| `C3 81` | `Á`     | letra `Á` maiúsculo com acento agudo |
| `C3 82` | `Â`     | letra `Â` maiúsculo com acento circunflexo |
| `C3 83` | `Ã`     | letra `Ã` maiúsculo com acento til |
| `C3 88` | `È`     | letra `È` maiúsculo com acento grave |
| `C3 89` | `É`     | letra `É` maiúsculo com acento agudo |
| `C3 8A` | `Ê`     | letra `Ê` maiúsculo com acento circunflexo |
| `C3 8C` | `Ì`     | letra `Ì` maiúsculo com acento grave |
| `C3 8D` | `Í`     | letra `Í` maiúsculo com acento agudo |
| `C3 8E` | `Î`     | letra `Î` maiúsculo com acento circunflexo |
| `C3 92` | `Ò`     | letra `Ò` maiúsculo com acento grave |
| `C3 93` | `Ó`     | letra `Ó` maiúsculo com acento agudo |
| `C3 94` | `Ô`     | letra `Ô` maiúsculo com acento circunflexo |
| `C3 95` | `Õ`     | letra `Õ` maiúsculo com acento til |
| `C3 99` | `Ù`     | letra `Ù` maiúsculo com acento grave |
| `C3 9A` | `Ú`     | letra `Ú` maiúsculo com acento agudo |
| `C3 9B` | `Û`     | letra `Û` maiúsculo com acento circunflexo |
| `C3 87` | `Ç`     | letra `Ç` maiúsculo com acento C cedilha |


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
