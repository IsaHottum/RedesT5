<h1>Questões Redes - Tema 5</h1>

<h3>1. Qual é a principal diferença entre os endereços IPv4 e IPv6 em termos de estrutura e quantidade de bits?</h3>
Os endereços do protocolo IPv4 são representados em notação decimal pontuada de 32 bits, enquanto os endereços do protocolo IPv6 são representados em notação hexadecimal de 128 bits. Isso resulta em um número significativamente maior de endereços disponíveis no IPv6 do que no IPv4.


<h3>2. Explique os três tipos de endereçamento do protocolo IPv6 (Unicast, Multicast e Anycast) e as funções de entrega de pacotes correspondentes.</h3>
<li>Unicast: identifica apenas uma interface de rede e fornece pacotes para apenas uma interface.</li>
<li>Multicast: cria um grupo de interfaces e envia pacotes para cada endereço dentro do grupo.</li>
<li>Anycast: Em contraste com o multicast, que entrega a todos os membros do grupo, o Anycast identifica um grupo de interfaces, mas entrega os pacotes apenas à interface mais próxima da origem.</li>


<h3>3. Como o cabeçalho IPv6 difere do cabeçalho IPv4 em termos de tamanho, campos e influência no processamento de pacotes pelos roteadores?</h3>
No IPv6, o cabeçalho é fixo em 64 bytes e contém campos como Version, Traffic Class, Flow Label, Payload Length, Next Header, Hop Limit, Source Address e Destination Address. Além de aumentar a eficiência da rede, essa estrutura fixa facilita o processamento de pacotes pelos roteadores.

<h3>4. Como o ICMPv6 difere do ICMPv4 em termos de funcionalidade e compatibilidade, e qual é sua importância para a comunicação IPv6?</h3>
O ICMPv6 é uma versão atualizada do protocolo ICMP para uso com IPv6. Ele mantém funções de diagnóstico e relatórios de erros, porém, incorpora funções de outros protocolos do IPv4. Essa integração simplifica a implementação e reduz a complexidade da rede IPv6, embora o ICMPv6 não seja compatível com o ICMPv4.
