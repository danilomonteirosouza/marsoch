# MARSOCH (Machine Learning Repository to Social Histories)

A *Communication Matrix*, foi publicada pela primeira vez em 1990 e revisada em 1996 pela Doutora Charity Rowland da Universidade Oregon Healthy & Science University, é um instrumento amplamente utilizado para a avaliação da comunicação funcional de indivíduos com ou sem deficiência, fundamentado na observação de comportamentos comunicativos em contextos naturais. O instrumento estrutura a comunicação a partir de três eixos centrais:

1. **Níveis de desenvolvimento comunicativo**  
2. **Funções comunicativas**  
3. **Meios de comunicação**

A base de dados aqui descrita constitui, portanto, uma **adaptação operacional da Communication Matrix**, preservando integralmente esses eixos, porém reorganizada em um formato estruturado, explícito e tratável computacionalmente.

É importante ressaltar que a base **não pretende substituir o instrumento original**, mas sim **operacionalizar seus construtos teóricos**, permitindo sua aplicação em sistemas inteligentes de apoio à comunicação, particularmente em **cenários de emergência**.

---

## Relação entre a base MARSOCH e a Communication Matrix (Rowland et al.)

A tabela a seguir apresenta o mapeamento estrutural entre os campos da base de dados **MARSOCH** e os componentes correspondentes da *Communication Matrix* proposta por Rowland et al. (2011).

| Campo da Base MARSOCH | Correspondência na Communication Matrix |
|----------------------|-----------------------------------------|
| `PessoaID` | Não aplicável (campo estrutural) |
| `NivelComunicacao` | Níveis de desenvolvimento comunicativo |
| `FuncaoComunicativa` | Funções comunicativas |
| `Ambiente` | Contexto de observação (implícito) |
| `ParceiroComunicacional` | Parceiro comunicativo (implícito) |
| `FormaPreferida` | Meios de comunicação |
| `DescricaoComportamento` | Comportamentos comunicativos observáveis |
| `PlanoIntervencao` | Resultados da avaliação aplicados à intervenção |
| `PlanoGuia` | Diretrizes derivadas da avaliação comunicativa |

---