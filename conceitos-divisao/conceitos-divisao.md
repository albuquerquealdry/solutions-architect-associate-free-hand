## Resumao: Conceito de divisao.

### Regiao, zona de disponibilidade, e borda de regiao:

* Regiao: Locais fisicos em todo mundo onde sao agrupados os datacenters da AWS. 

* Zona de disponibilidade: Cada grupo logico de datacenter que tem energia, rede e conectividade redundante em uma regiao da AWS. Cada AZ tem energia, refrigeração e segurança física independentes e está conectada por meio de redes redundantes de latência ultrabaixa. As AZs são fisicamente separadas por uma distância significativa (vários quilômetros) das outras AZs, embora todas estejam em um raio de até 100 km entre si.

* Bordas de região: Trasmite entrega de conteudo com melhor latencia para usuario em todo mundo. Sao locais de entrega de conteudo presentes em cada regiao.
OBS: Lembrar sempre do cloudfront CDN.