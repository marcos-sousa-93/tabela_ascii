
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
| `80`    | 128     | `Ç`       | C cedilha maiúscula               | |
| `81`    | 129     | `ü`       | u com trema                       | |
| `82`    | 130     | `é`       | e agudo                           | |
| `83`    | 131     | `â`       | a circunflexo                     | |
| `84`    | 132     | `ä`       | a com trema                       | |
| `85`    | 133     | `à`       | a grave                           | |
| `86`    | 134     | `å`       | a com anel                        | |
| `87`    | 135     | `ç`       | c cedilha minúscula               | |
| `88`    | 136     | `ê`       | e circunflexo                     | |
| `89`    | 137     | `ë`       | e com trema                       | |
| `8A`    | 138     | `è`       | e grave                           | |
| `8B`    | 139     | `ï`       | i com trema                       | |
| `8C`    | 140     | `î`       | i circunflexo                     | |
| `8D`    | 141     | `ì`       | i grave                           | |
| `8E`    | 142     | `Ä`       | A com trema                       | |
| `8F`    | 143     | `Å`       | A com anel                        | |
| `90`    | 144     | `É`       | E agudo                           | |
| `91`    | 145     | `æ`       | Ligatura ae                       | |
| `92`    | 146     | `Æ`       | Ligatura AE                       | |
| `93`    | 147     | `ô`       | o circunflexo                     | |
| `94`    | 148     | `ö`       | o com trema                       | |
| `95`    | 149     | `ò`       | o grave                           | |
| `96`    | 150     | `û`       | u circunflexo                     | |
| `97`    | 151     | `ù`       | u grave                           | |
| `98`    | 152     | `ÿ`       | y com trema                       | |
| `99`    | 153     | `Ö`       | O com trema                       | |
| `9A`    | 154     | `Ü`       | U com trema                       | |
| `9B`    | 155     | `¢`       | Centavo                           | |
| `9C`    | 156     | `£`       | Libra esterlina                   | |
| `9D`    | 157     | `¥`       | Yen                               | |
| `9E`    | 158     | `₧`       | Peseta                            | |
| `9F`    | 159     | `ƒ`       | Florim                            | |
| `A0`    | 160     | `á`       | a agudo                           | |
| `A1`    | 161     | `í`       | i agudo                           | |
| `A2`    | 162     | `ó`       | o agudo                           | |
| `A3`    | 163     | `ú`       | u agudo                           | |
| `A4`    | 164     | `ñ`       | n com til                         | |
| `A5`    | 165     | `Ñ`       | N com til                         | |
| `A6`    | 166     | `ª`       | Ordem feminina                    | |
| `A7`    | 167     | `º`       | Ordem masculina                   | |
| `A8`    | 168     | `¿`       | Interrogação invertida            | |
| `A9`    | 169     | `⌐`       | Símbolo gráfico                   | |
| `AA`    | 170     | `¬`       | Negação                           | |
| `AB`    | 171     | `½`       | Meio                              | |
| `AC`    | 172     | `¼`       | Um quarto                         | |
| `AD`    | 173     | `¡`       | Exclamação invertida              | |
| `AE`    | 174     | `«`       | Aspas angulares esquerda          | |
| `AF`    | 175     | `»`       | Aspas angulares direita           | |
| `B0`    | 176     | `░`       | Bloco claro                       | |
| `B1`    | 177     | `▒`       | Bloco médio                       | |
| `B2`    | 178     | `▓`       | Bloco escuro                      | |
| `B3`    | 179     | `│`       | Linha vertical                    | |
| `B4`    | 180     | `┤`       | Linha vertical + direita          | |
| `B5`    | 181     | `╡`       | Linha vertical dupla              | |
| `B6`    | 182     | `╢`       | Linha vertical dupla + direita    | |
| `B7`    | 183     | `╖`       | Canto superior esquerdo           | |
| `B8`    | 184     | `╕`       | Canto superior direito            | |
| `B9`    | 185     | `╣`       | Linha vertical dupla + esquerda   | |
| `BA`    | 186     | `║`       | Linha vertical dupla              | |
| `BB`    | 187     | `╗`       | Canto inferior direito            | |
| `BC`    | 188     | `╝`       | Canto inferior esquerdo           | |
| `BD`    | 189     | `╜`       | Canto inferior esquerdo duplo     | |
| `BE`    | 190     | `╛`       | Canto inferior direito duplo      | |
| `BF`    | 191     | `┐`       | Canto superior direito            | |
| `C0`    | 192     | `└`       | Canto inferior esquerdo           | |
| `C1`    | 193     | `┴`       | Linha horizontal inferior         | |
| `C2`    | 194     | `┬`       | Linha horizontal superior         | |
| `C3`    | 195     | `├`       | Linha vertical + esquerda         | |
| `C4`    | 196     | `─`       | Linha horizontal                  | |
| `C5`    | 197     | `┼`       | Cruz                              | |
| `C6`    | 198     | `╞`       | Linha vertical dupla + esquerda   | |
| `C7`    | 199     | `╟`       | Linha vertical dupla + direita    | |
| `C8`    | 200     | `╚`       | Canto inferior esquerdo duplo     | |
| `C9`    | 201     | `╔`       | Canto superior esquerdo duplo     | |
| `CA`    | 202     | `╩`       | Linha horizontal inferior dupla   | |
| `CB`    | 203     | `╦`       | Linha horizontal superior dupla   | |
| `CC`    | 204     | `╠`       | Linha vertical dupla + esquerda   | |
| `CD`    | 205     | `═`       | Linha horizontal dupla            | |
| `CE`    | 206     | `╬`       | Cruz dupla                        | |
| `CF`    | 207     | `╧`       | Linha horizontal inferior dupla   | |
| `D0`    | 208     | `╨`       | Linha horizontal inferior dupla   | |
| `D1`    | 209     | `╤`       | Linha horizontal superior dupla   | |
| `D2`    | 210     | `╥`       | Linha horizontal superior dupla   | |
| `D3`    | 211     | `╙`       | Canto inferior direito duplo      | |
| `D4`    | 212     | `╘`       | Canto inferior esquerdo duplo     | |
| `D5`    | 213     | `╒`       | Canto superior esquerdo duplo     | |
| `D6`    | 214     | `╓`       | Canto superior direito duplo      | |
| `D7`    | 215     | `╫`       | Cruz dupla                        | |
| `D8`    | 216     | `╪`       | Cruz dupla                        | |
| `D9`    | 217     | `┘`       | Canto inferior direito            | |
| `DA`    | 218     | `┌`       | Canto superior esquerdo           | |
| `DB`    | 219     | `█`       | Bloco sólido                      | |
| `DC`    | 220     | `▄`       | Metade inferior do bloco          | |
| `DD`    | 221     | `▌`       | Metade esquerda do bloco          | |
| `DE`    | 222     | `▐`       | Metade direita do bloco           | |
| `DF`    | 223     | `▀`       | Metade superior do bloco          | |
| `E0`    | 224     | `α`       | Letra grega alfa                  | |
| `E1`    | 225     | `ß`       | Letra alemã beta                  | |
| `E2`    | 226     | `Γ`       | Letra grega gama                  | |
| `E3`    | 227     | `π`       | Letra grega pi                    | |
| `E4`    | 228     | `Σ`       | Letra grega sigma                 | |
| `E5`    | 229     | `σ`       | Letra grega sigma minúscula       | |
| `E6`    | 230     | `µ`       | Micro                             | |
| `E7`    | 231     | `τ`       | Letra grega tau                   | |
| `E8`    | 232     | `Φ`       | Letra grega phi                   | |
| `E9`    | 233     | `Θ`       | Letra grega theta                 | |
| `EA`    | 234     | `Ω`       | Letra grega omega                 | |
| `EB`    | 235     | `δ`       | Letra grega delta                 | |
| `EC`    | 236     | `∞`       | Infinito                          | |
| `ED`    | 237     | `φ`       | Letra grega phi minúscula         | |
| `EE`    | 238     | `ε`       | Letra grega epsilon               | |
| `EF`    | 239     | `∩`       | Interseção                        | |
| `F0`    | 240     | `≡`       | Equivalente                       | |
| `F1`    | 241     | `±`       | Mais ou menos                     | | 
| `F2`    | 242     | `≥`       | Maior ou igual                    | | 
| `F3`    | 243     | `≤`       | Menor ou igual                    | | 
| `F4`    | 244     | `⌠`       | Integral superior                 | |
| `F5`    | 245     | `⌡`       | Integral inferior                 | |
| `F6`    | 246     | `÷`       | Divisão                           | |
| `F7`    | 247     | `≈`       | Aproximadamente                   | |
| `F8`    | 248     | `°`       | Grau                              | |
| `F9`    | 249     | `∙`       | Ponto de operação                 | |
| `FA`    | 250     | `·`       | Ponto central                     | |
| `FB`    | 251     | `√`       | Raiz quadrada                     | |
| `FC`    | 252     | `ⁿ`       | Expoente n                        | |
| `FD`    | 253     | `²`       | Expoente 2                        | |
| `FE`    | 254     | `■`       | Quadrado preto                    | |
| `FF`    | 255     | ` `       | Espaço sem quebra                 | |

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
