Seja bem vindos a página do GITHUB do CasinoDoge.org, aqui vamos tentar explicar como o nosso sistema é seguro, justo e leal com os nossos usuários! Então vamos lá =)

PROVABLY FAIR
O sistema PROVABLY FAIR é utilizado em na maioria dos grandes casinos online em todo o mundo!

O sistema é o seguinte, fazemos um calculo com DUAS HASHS uma é do cliente e uma do servidor.

A HASH(semente) do cliente é sempre aberta e divulgada a todos(você pode inclusive pedir sempre para mudar ela)!

A HASH(semente) do servidor é divulgada, porém ela é protegida em SHA256!

Portanto, se ANTES de você rolar os dados, você anotar as duas sementes(cliente e servidor), após rolar os dados, iremos abrir para você a HASH(semente) do servidor sem o SHA256!

Apos abrirmos para você, basta você comparar se o SHA256 bate com a semente aberta, isso quer dizer que utilizamos a mesma semente que mostramos para você, parece complicado mais é bem simples!

Após isso você pode simular a rodada do dado, em vários sites que disponibilizam esse calculo: https://dicesites.com/primedice/verifier?game=dice (colocando o last nonce sempre como 0)

O algoritimo pode ser visto aqui na ClassDice.cs, aqui no nosso github!

Temos uma explicação bem completa aqui: https://dicesites.com/provably-fair

Também temos uma explicação legal no wikipedia: https://en.wikipedia.org/wiki/Provably_fair_algorithm

Whitepaper do algoritmo: https://cryptogambling.org/whitepapers/provably-fair-algorithms.pdf

Ou seja nosso casino não depende de terceiros é totalmente auditado pelos usuários!
