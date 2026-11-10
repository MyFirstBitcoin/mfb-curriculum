# 2.5 Blockkedjan: Bitcoins offentliga huvudbok

<!-- card: definition -->
> **Definition – Blockkedja**
>
> Bitcoins [blockkedja](https://curriculum.myfirstbitcoin.org/lexicon/en/#blockchain) är ett offentligt [transaktionsregister](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) som replikeras på många oberoende datorer. Ett block samlar en uppsättning giltiga [transaktioner](https://curriculum.myfirstbitcoin.org/lexicon/en/#transaction) till nästa föreslagna del av registret. Varje giltigt block länkar till det föregående, vilket ger nätverket en ordnad, gemensam historik att verifiera.



<!-- card: light -->
> **Hur noder når konsensus**
>
> [Noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) kontrollerar oberoende av varandra samma regler och enas om den giltiga historik som har störst mängd ackumulerat [arbetsbevis](https://curriculum.myfirstbitcoin.org/lexicon/en/#proof-of-work). Om en tidigare post ändras, ändras dess block och länkarna till senare block bryts. En konkurrerande historik måste därför göra om detta arbete och komma ikapp innan [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) accepterar den. Denna kostsamma process för att fastställa ordningen hjälper nätverket att nå [konsensus](https://curriculum.myfirstbitcoin.org/lexicon/en/#consensus) utan en central registeransvarig. Kopior ändras inte samtidigt; [noder](https://curriculum.myfirstbitcoin.org/lexicon/en/#node) tar emot och validerar data oberoende av varandra. Bitcoin siktar på ett nytt block ungefär var tionde minut i genomsnitt. Historiken är svår och kostsam att skriva om, men inte bokstavligen omöjlig att ändra: tillfälliga konkurrerande historiker och omorganisationer kan förekomma.
