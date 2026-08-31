# Resumo — Sistemas Operacionais Modernos

## Andrew S. Tanenbaum e Herbert Bos — 4ª edição

**Referência:** TANENBAUM, Andrew S.; BOS, Herbert. *Sistemas Operacionais Modernos*. 4. ed. São Paulo: Pearson, 2016.

---

# CAPÍTULO 8 — MULTIPROCESSADORES

1. Multiprocessadores são sistemas que possuem dois ou mais processadores ou núcleos de processamento.
2. O objetivo principal é aumentar o desempenho e permitir a execução concorrente de tarefas.
3. Sistemas com vários processadores podem executar diferentes tarefas simultaneamente.
4. A utilização de múltiplos processadores exige mecanismos específicos do Sistema Operacional.
5. O Sistema Operacional precisa distribuir o trabalho entre os processadores.
6. Essa distribuição é chamada de escalonamento.
7. Em sistemas multiprocessados, vários processadores podem compartilhar recursos.
8. Memória e dispositivos podem ser compartilhados entre os processadores.
9. A comunicação entre processadores é importante para a execução correta das tarefas.
10. Um dos desafios é evitar conflitos quando diferentes processadores acessam o mesmo recurso.
11. A sincronização é fundamental em sistemas multiprocessados.
12. Processos diferentes podem ser executados em processadores diferentes.
13. Threads também podem ser distribuídas entre diferentes núcleos.
14. O paralelismo permite executar atividades simultaneamente.
15. Concorrência e paralelismo são conceitos relacionados, mas não são exatamente iguais.
16. Concorrência significa lidar com várias tarefas que avançam de forma intercalada.
17. Paralelismo significa executar tarefas simultaneamente em diferentes unidades de processamento.
18. Processadores modernos normalmente possuem vários núcleos.
19. Cada núcleo pode executar instruções independentemente.
20. O Sistema Operacional precisa conhecer a quantidade de processadores disponíveis.
21. O escalonador decide onde e quando uma tarefa será executada.
22. O balanceamento de carga busca distribuir o trabalho adequadamente.
23. Um processador não deve ficar sobrecarregado enquanto outro permanece ocioso.
24. O balanceamento melhora o aproveitamento dos recursos.
25. Sistemas multiprocessadores podem utilizar memória compartilhada.
26. Na memória compartilhada, os processadores acessam uma mesma memória principal.
27. A comunicação por memória compartilhada pode ser rápida.
28. Porém, o acesso simultâneo pode provocar condições de corrida.
29. Uma condição de corrida ocorre quando o resultado depende da ordem dos acessos.
30. A sincronização ajuda a evitar condições de corrida.
31. Sem sincronização, dados compartilhados podem ficar inconsistentes.
32. Semáforos são mecanismos utilizados para sincronização.
33. Mutex também pode ser utilizado para proteger regiões críticas.
34. Uma região crítica é uma parte do programa que acessa recursos compartilhados.
35. Apenas uma quantidade permitida de processos ou threads deve acessar determinada região crítica.
36. O controle de acesso evita alterações simultâneas inadequadas.
37. Sistemas multiprocessadores também precisam lidar com coerência de cache.
38. Caches armazenam temporariamente dados utilizados pelo processador.
39. Dois processadores podem possuir cópias diferentes de uma mesma informação.
40. A coerência de cache mantém essas cópias consistentes.
41. Multiprocessadores podem apresentar diferentes organizações de memória.
42. Em sistemas UMA, o acesso à memória possui características semelhantes para os processadores.
43. Em sistemas NUMA, o tempo de acesso pode depender da localização da memória.
44. NUMA significa acesso não uniforme à memória.
45. O Sistema Operacional precisa considerar a arquitetura disponível.
46. A afinidade de processador permite associar tarefas a determinados processadores.
47. A afinidade pode melhorar desempenho em determinadas situações.
48. Migrar uma tarefa entre processadores pode ter custos.
49. O objetivo do escalonamento é aproveitar os processadores de forma eficiente.
50. Multiprocessamento aumenta o desempenho, mas também aumenta a complexidade do Sistema Operacional.

---

# CAPÍTULO 9 — SEGURANÇA

51. Segurança é uma das funções fundamentais dos Sistemas Operacionais.
52. O objetivo é proteger dados, programas e recursos.
53. O sistema precisa impedir acessos não autorizados.
54. Segurança envolve confidencialidade, integridade e disponibilidade.
55. Confidencialidade significa impedir que informações sejam acessadas por pessoas não autorizadas.
56. Integridade significa impedir alterações indevidas.
57. Disponibilidade significa manter recursos acessíveis quando necessários.
58. Autenticação verifica quem é o usuário.
59. Autorização determina o que o usuário pode fazer.
60. Identificação informa quem está tentando acessar o sistema.
61. Senhas são um mecanismo tradicional de autenticação.
62. Senhas fracas podem comprometer a segurança.
63. Uma senha deve ser difícil de descobrir.
64. Sistemas modernos podem utilizar autenticação multifator.
65. Autenticação multifator utiliza mais de uma forma de comprovar identidade.
66. O Sistema Operacional deve controlar permissões.
67. Permissões determinam quais operações podem ser realizadas.
68. Arquivos podem possuir diferentes níveis de acesso.
69. Um usuário pode ter permissão para ler um arquivo.
70. Outro usuário pode ter permissão para modificar o arquivo.
71. O controle de acesso reduz riscos.
72. O princípio do menor privilégio é importante.
73. Pelo menor privilégio, cada usuário ou processo deve possuir somente os privilégios necessários.
74. Conceder privilégios excessivos aumenta os riscos.
75. O Sistema Operacional também precisa proteger a memória.
76. Um processo não deve acessar livremente a memória de outro processo.
77. A separação de processos ajuda a evitar interferências.
78. O modo usuário limita o acesso das aplicações.
79. O modo kernel possui privilégios maiores.
80. Essa separação contribui para a segurança.
81. Um programa malicioso pode tentar explorar vulnerabilidades.
82. Malware é um termo utilizado para programas maliciosos.
83. Vírus são programas capazes de se espalhar de determinadas maneiras.
84. Worms podem se propagar por redes.
85. Cavalos de Troia são programas que aparentam ter outra finalidade.
86. Spyware pode tentar coletar informações do usuário.
87. Ransomware pode bloquear ou criptografar dados para exigir pagamento.
88. Rootkits procuram obter ou manter acesso privilegiado ao sistema.
89. Sistemas Operacionais precisam utilizar mecanismos de proteção contra malware.
90. Atualizações de segurança corrigem vulnerabilidades conhecidas.
91. Uma vulnerabilidade é uma fraqueza que pode ser explorada.
92. Ataques podem ocorrer por software ou pela rede.
93. Sistemas conectados à internet precisam de mecanismos adicionais de proteção.
94. Firewalls podem controlar determinadas conexões de rede.
95. Criptografia protege informações transformando-as em uma forma que dificulta o acesso indevido.
96. Dados criptografados precisam de uma chave para serem recuperados.
97. A segurança também depende do comportamento dos usuários.
98. Engenharia social explora pessoas para obter informações ou acesso.
99. Segurança absoluta é difícil de alcançar.
100. O objetivo é reduzir riscos por meio de várias camadas de proteção.

---

# CAPÍTULO 10 — MULTIMÍDIA

101. Sistemas multimídia trabalham com diferentes tipos de informação.
102. Exemplos incluem áudio, vídeo, imagens e animações.
103. Multimídia apresenta desafios específicos para Sistemas Operacionais.
104. Muitos dados multimídia precisam ser processados continuamente.
105. Áudio e vídeo normalmente possuem requisitos de tempo.
106. Atrasos podem prejudicar a qualidade da reprodução.
107. Por isso, sistemas multimídia precisam considerar tempo e desempenho.
108. Streaming é a transmissão contínua de dados multimídia.
109. No streaming, os dados são recebidos enquanto são reproduzidos.
110. A rede precisa entregar os dados com velocidade suficiente.
111. Se os dados chegarem muito tarde, pode ocorrer interrupção.
112. Buffer é uma área utilizada para armazenar temporariamente dados.
113. O buffer ajuda a compensar pequenas variações na velocidade da rede.
114. Sistemas multimídia podem utilizar buffers de reprodução.
115. Áudio possui características diferentes de arquivos comuns.
116. O áudio precisa ser processado em uma taxa específica.
117. Vídeo também possui uma sequência de quadros.
118. A taxa de quadros influencia a qualidade percebida.
119. Sistemas de tempo real possuem requisitos temporais.
120. Em sistemas de tempo real, algumas tarefas precisam ser executadas dentro de prazos.
121. Perder um prazo pode causar problemas no funcionamento.
122. Sistemas de tempo real podem ser classificados em diferentes categorias.
123. Em sistemas rígidos, perder um prazo pode ser considerado uma falha grave.
124. Em sistemas flexíveis, pequenos atrasos podem ser tolerados.
125. O escalonamento precisa considerar prioridades temporais.
126. Tarefas multimídia podem precisar de prioridade adequada.
127. O Sistema Operacional precisa administrar CPU, memória e dispositivos.
128. Dispositivos multimídia podem produzir grandes quantidades de dados.
129. A transferência de dados precisa ser eficiente.
130. DMA permite que determinados dispositivos transfiram dados para a memória com pouca intervenção da CPU.
131. DMA significa Direct Memory Access.
132. O DMA pode reduzir a carga sobre o processador.
133. Dispositivos de áudio e vídeo podem utilizar técnicas semelhantes.
134. Compressão reduz o tamanho dos dados.
135. Compressão pode ser com ou sem perda.
136. Compressão sem perda permite recuperar os dados originais.
137. Compressão com perda remove algumas informações para obter arquivos menores.
138. Formatos multimídia utilizam diferentes métodos de codificação.
139. Codecs são utilizados para codificar e decodificar dados.
140. Reprodução multimídia exige cooperação entre software e hardware.
141. O processador executa tarefas de processamento.
142. A memória armazena dados temporariamente.
143. A placa de vídeo pode auxiliar no processamento gráfico.
144. Dispositivos de armazenamento guardam arquivos multimídia.
145. A rede pode transportar áudio e vídeo.
146. A latência representa o atraso na transmissão ou processamento.
147. Jitter representa variações no atraso.
148. Latência e jitter podem afetar aplicações em tempo real.
149. Videoconferências são exemplos de aplicações sensíveis a esses problemas.
150. Sistemas Operacionais precisam equilibrar desempenho, recursos e requisitos temporais.

---

# CAPÍTULO 11 — SISTEMAS MULTIMÍDIA E PROCESSAMENTO EM TEMPO REAL

151. Aplicações em tempo real possuem requisitos relacionados ao tempo.
152. O resultado correto depende não apenas do que é produzido, mas também de quando é produzido.
153. Sistemas tradicionais geralmente priorizam desempenho médio.
154. Sistemas de tempo real precisam considerar prazos.
155. Uma tarefa pode ter um deadline.
156. Deadline é o prazo máximo para concluir uma determinada atividade.
157. O escalonador precisa considerar esses prazos.
158. Prioridades podem ser atribuídas às tarefas.
159. Tarefas críticas podem receber prioridade maior.
160. Um atraso excessivo pode comprometer o funcionamento da aplicação.
161. Sistemas de tempo real são utilizados em diversas áreas.
162. Automação industrial é um exemplo.
163. Sistemas embarcados também podem possuir requisitos de tempo real.
164. Equipamentos médicos podem utilizar processamento em tempo real.
165. Sistemas automotivos podem depender de respostas rápidas.
166. Aplicações multimídia também podem apresentar requisitos temporais.
167. Áudio e vídeo precisam ser processados em ritmo adequado.
168. O Sistema Operacional precisa reduzir atrasos imprevisíveis.
169. O escalonamento é uma das partes mais importantes.
170. Algoritmos de escalonamento podem utilizar prioridades.
171. Uma abordagem comum é atribuir prioridades conforme características das tarefas.
172. Tarefas periódicas são executadas repetidamente em intervalos.
173. Tarefas aperiódicas não possuem intervalo fixo.
174. Tarefas periódicas aparecem frequentemente em sistemas de controle.
175. O período define o intervalo entre execuções.
176. O tempo de execução representa quanto tempo a tarefa precisa do processador.
177. O deadline determina até quando ela precisa terminar.
178. Esses valores ajudam a planejar o escalonamento.
179. Um sistema precisa verificar se consegue atender aos requisitos.
180. Sobrecarga pode provocar perda de deadlines.
181. Recursos insuficientes comprometem sistemas de tempo real.
182. O Sistema Operacional precisa controlar interrupções.
183. Interrupções permitem que dispositivos chamem a atenção do processador.
184. Interrupções são importantes para sistemas responsivos.
185. Temporizadores ajudam a controlar atividades relacionadas ao tempo.
186. Um timer pode gerar interrupções periodicamente.
187. O escalonador pode utilizar temporizadores para controlar a execução.
188. A previsibilidade é importante em tempo real.
189. Uma resposta rápida, mas imprevisível, pode não ser suficiente.
190. O objetivo é garantir comportamento dentro dos limites definidos.
191. Sistemas de tempo real não significam necessariamente sistemas muito rápidos.
192. O principal requisito é cumprir as restrições temporais.
193. Um sistema pode ser rápido, mas não determinístico.
194. Determinismo significa conseguir prever o comportamento dentro de determinados limites.
195. Recursos compartilhados podem dificultar o atendimento de deadlines.
196. Bloqueios podem atrasar tarefas importantes.
197. Sincronização precisa ser cuidadosamente planejada.
198. Prioridades podem gerar problemas quando tarefas compartilham recursos.
199. O projeto do Sistema Operacional precisa considerar esses conflitos.
200. Tempo real exige integração entre hardware, software e Sistema Operacional.

---

# CAPÍTULO 12 — SISTEMAS OPERACIONAIS EM DISPOSITIVOS MÓVEIS

201. Dispositivos móveis possuem características diferentes dos computadores tradicionais.
202. Smartphones e tablets possuem limitações específicas.
203. Energia é um recurso extremamente importante.
204. Processamento consome energia.
205. Comunicação sem fio também consome energia.
206. A tela é um dos componentes que pode consumir bastante energia.
207. Sistemas móveis precisam controlar cuidadosamente o consumo.
208. O gerenciamento de energia é uma função importante.
209. Processadores móveis podem alterar sua frequência.
210. Reduzir a frequência pode diminuir o consumo de energia.
211. Sistemas móveis também utilizam múltiplos núcleos.
212. O Sistema Operacional precisa distribuir tarefas entre os núcleos.
213. Memória também é limitada em comparação com alguns computadores.
214. O gerenciamento eficiente da memória é essencial.
215. Aplicativos móveis precisam compartilhar recursos.
216. O Sistema Operacional precisa controlar o acesso entre aplicativos.
217. Segurança é especialmente importante em dispositivos móveis.
218. Aplicativos podem acessar informações pessoais.
219. Exemplos incluem contatos, localização e câmera.
220. Permissões controlam o acesso dos aplicativos.
221. O usuário pode autorizar ou negar determinadas permissões.
222. O isolamento entre aplicativos reduz riscos.
223. Um aplicativo não deve acessar livremente os dados de outro.
224. Sandboxing é uma técnica utilizada para limitar aplicativos.
225. Um aplicativo pode executar em um ambiente isolado.
226. Sistemas móveis também possuem mecanismos de autenticação.
227. Senhas, PINs e biometria podem ser utilizados.
228. Atualizações de segurança são importantes.
229. Dispositivos móveis normalmente possuem conexão sem fio.
230. Wi-Fi é utilizado para redes locais.
231. Redes celulares permitem comunicação móvel.
232. Bluetooth permite comunicação de curto alcance.
233. O Sistema Operacional precisa gerenciar essas interfaces.
234. Aplicações móveis podem funcionar em segundo plano.
235. Processos em segundo plano consomem recursos.
236. O Sistema Operacional pode limitar essas atividades.
237. Essa limitação ajuda a preservar bateria.
238. Notificações permitem informar o usuário sem manter todos os aplicativos ativos.
239. Sistemas móveis possuem diferentes estados de energia.
240. Um dispositivo pode entrar em modo de suspensão.
241. A suspensão reduz o consumo enquanto o dispositivo não está sendo utilizado.
242. A retomada precisa ocorrer rapidamente quando necessário.
243. Sistemas móveis também precisam administrar armazenamento.
244. Aplicativos precisam de espaço para seus dados.
245. Arquivos multimídia podem ocupar grande quantidade de armazenamento.
246. O Sistema Operacional organiza esses dados.
247. Interfaces móveis são projetadas para telas sensíveis ao toque.
248. Gestos são utilizados como forma de entrada.
249. O Sistema Operacional transforma os gestos em eventos para as aplicações.
250. Sistemas móveis precisam equilibrar desempenho, segurança, usabilidade e consumo de energia.

---

# CAPÍTULO 13 — SISTEMAS OPERACIONAIS PARA MULTICOMPUTADORES E SISTEMAS DISTRIBUÍDOS

251. Sistemas distribuídos possuem vários computadores trabalhando em conjunto.
252. Os computadores podem estar conectados por uma rede.
253. Cada máquina possui seu próprio processador e memória.
254. A comunicação ocorre principalmente por meio da rede.
255. O objetivo pode ser compartilhar recursos e executar tarefas de maneira cooperativa.
256. Sistemas distribuídos podem aumentar a capacidade de processamento.
257. Também podem melhorar disponibilidade e tolerância a falhas.
258. Uma aplicação distribuída pode executar partes diferentes em computadores diferentes.
259. A comunicação entre máquinas é essencial.
260. Uma rede pode apresentar atrasos.
261. A comunicação também pode falhar.
262. Portanto, sistemas distribuídos precisam lidar com problemas de comunicação.
263. Uma mensagem pode ser atrasada.
264. Uma mensagem pode ser perdida.
265. Um computador pode ficar indisponível.
266. O Sistema Operacional precisa considerar essas possibilidades.
267. Sistemas distribuídos podem compartilhar arquivos.
268. Sistemas de arquivos distribuídos permitem acessar dados pela rede.
269. O usuário pode perceber os dados como se estivessem em um único sistema.
270. Transparência é uma característica importante.
271. Transparência significa esconder determinados detalhes da distribuição.
272. Um sistema pode tentar esconder onde um recurso está localizado.
273. RPC significa Remote Procedure Call.
274. RPC permite que um programa solicite uma operação em outro computador.
275. A ideia é tornar a comunicação mais parecida com uma chamada de procedimento local.
276. A comunicação de rede possui custos.
277. Uma chamada remota é geralmente mais lenta que uma chamada local.
278. Programas distribuídos precisam considerar essa diferença.
279. Sincronização entre computadores é outro desafio.
280. Relógios de máquinas diferentes podem apresentar diferenças.
281. Sistemas distribuídos precisam de mecanismos para ordenar eventos.
282. A ordenação de eventos ajuda a entender relações entre operações.
283. Algoritmos distribuídos coordenam atividades entre máquinas.
284. Eleição de líder é um exemplo de problema distribuído.
285. Um grupo de máquinas pode precisar escolher um coordenador.
286. Outro problema é a exclusão mútua distribuída.
287. Ela controla acesso a recursos compartilhados entre diferentes máquinas.
288. Falhas são especialmente importantes em sistemas distribuídos.
289. Uma máquina pode falhar enquanto outras continuam funcionando.
290. O sistema precisa detectar ou contornar essas falhas.
291. Redundância pode aumentar a disponibilidade.
292. Replicação significa manter cópias de dados ou serviços.
293. Se uma cópia falhar, outra pode continuar disponível.
294. Replicação pode melhorar tolerância a falhas.
295. Porém, manter cópias consistentes é um desafio.
296. Se uma informação mudar em uma máquina, outras cópias podem precisar ser atualizadas.
297. Consistência define como as cópias devem se comportar.
298. Sistemas distribuídos podem utilizar diferentes modelos de consistência.
299. Segurança também é necessária em ambientes distribuídos.
300. Comunicação pela rede pode ser alvo de ataques.
301. Autenticação verifica quem está se comunicando.
302. Criptografia pode proteger os dados transmitidos.
303. Autorização controla quais operações podem ser realizadas.
304. Sistemas distribuídos podem utilizar servidores.
305. Servidores oferecem recursos ou serviços.
306. Clientes solicitam esses serviços.
307. Esse modelo é conhecido como cliente-servidor.
308. Outro modelo é o peer-to-peer.
309. No peer-to-peer, os participantes podem atuar como clientes e servidores.
310. Sistemas distribuídos são utilizados em aplicações modernas.
311. Serviços de internet são exemplos importantes.
312. Computação em nuvem utiliza grandes conjuntos de computadores.
313. Data centers reúnem muitos servidores.
314. A distribuição permite compartilhar carga entre máquinas.
315. Balanceamento de carga distribui requisições.
316. O objetivo é evitar sobrecarga em determinados servidores.
317. Sistemas distribuídos podem ser escaláveis.
318. Escalabilidade significa conseguir aumentar a capacidade conforme a demanda.
319. Adicionar máquinas pode aumentar a capacidade de processamento.
320. Porém, distribuir tarefas também aumenta a complexidade.
321. A rede passa a fazer parte fundamental do sistema.
322. Falhas de rede precisam ser consideradas.
323. Latência influencia o desempenho.
324. Sistemas distribuídos precisam considerar sincronização.
325. Sistemas distribuídos permitem construir serviços de grande escala.

---

# RELAÇÃO ENTRE OS CAPÍTULOS 8 A 13

326. Os capítulos mostram diferentes desafios enfrentados pelos Sistemas Operacionais.
327. O capítulo 8 trata principalmente do uso de múltiplos processadores.
328. O capítulo 9 aborda proteção e segurança.
329. O capítulo 10 aborda sistemas multimídia.
330. O capítulo 11 apresenta desafios relacionados ao tempo real.
331. O capítulo 12 trata de dispositivos móveis.
332. O capítulo 13 trata de sistemas distribuídos.
333. Todos esses temas dependem do gerenciamento eficiente de recursos.
334. Processador é um recurso fundamental.
335. Memória é outro recurso fundamental.
336. Armazenamento também precisa ser administrado.
337. Dispositivos de Entrada e Saída precisam ser controlados.
338. Processos precisam ser organizados.
339. Threads precisam ser sincronizadas quando compartilham recursos.
340. Segurança precisa proteger todos esses recursos.
341. O kernel possui papel central nesse gerenciamento.
342. O kernel executa com privilégios elevados.
343. Aplicações normalmente executam em modo usuário.
344. Essa separação ajuda a proteger o sistema.
345. Processos não devem acessar livremente os recursos de outros processos.
346. A sincronização evita conflitos.
347. O escalonamento determina como o processador será utilizado.
348. Em multiprocessadores, o escalonamento precisa considerar vários núcleos.
349. Em tempo real, o escalonamento também precisa considerar prazos.
350. Em sistemas móveis, o escalonamento precisa considerar consumo de energia.
351. Em sistemas distribuídos, o processamento pode ser dividido entre máquinas.
352. Em multimídia, o escalonamento precisa considerar fluxo contínuo de dados.
353. Portanto, o mesmo conceito pode possuir desafios diferentes dependendo do sistema.

---

# CONCEITOS MAIS IMPORTANTES PARA PROVA

354. **Processo** é um programa em execução.
355. **Thread** é uma unidade de execução dentro de um processo.
356. Processos podem possuir várias threads.
357. Threads podem compartilhar recursos do processo.
358. O compartilhamento exige sincronização.
359. **Kernel** é o núcleo do Sistema Operacional.
360. O kernel gerencia recursos fundamentais.
361. **Modo usuário** possui menos privilégios.
362. **Modo kernel** possui privilégios elevados.
363. A separação aumenta segurança e estabilidade.
364. **Escalonamento** organiza o uso do processador.
365. O escalonador decide quais tarefas executar.
366. **Concorrência** envolve várias tarefas progredindo.
367. **Paralelismo** permite execução simultânea.
368. Multiprocessadores permitem maior paralelismo.
369. **Condição de corrida** ocorre quando o resultado depende da ordem dos acessos.
370. **Região crítica** é uma parte que acessa recursos compartilhados.
371. **Mutex** pode proteger uma região crítica.
372. **Semáforo** é um mecanismo de sincronização.
373. **Deadlock** ocorre quando processos ficam esperando recursos uns dos outros.
374. Segurança protege recursos e informações.
375. **Autenticação** verifica a identidade.
376. **Autorização** define permissões.
377. **Princípio do menor privilégio** reduz riscos.
378. **Criptografia** protege informações.
379. **Firewall** controla determinados fluxos de rede.
380. **Malware** é software malicioso.
381. Sistemas multimídia trabalham com áudio, vídeo e outros dados.
382. Streaming transmite dados continuamente.
383. Buffer armazena dados temporariamente.
384. Latência representa atraso.
385. Jitter representa variação no atraso.
386. **Tempo real** possui requisitos temporais.
387. Deadline é o prazo para conclusão de uma tarefa.
388. Sistemas de tempo real precisam ser previsíveis.
389. Sistemas móveis precisam economizar energia.
390. Aplicativos móveis precisam ser isolados.
391. Permissões protegem recursos do dispositivo.
392. Sistemas distribuídos utilizam vários computadores.
393. Comunicação em sistemas distribuídos ocorre principalmente pela rede.
394. Falhas de rede são um desafio.
395. Replicação pode aumentar disponibilidade.
396. Consistência é importante quando existem várias cópias.
397. RPC permite solicitar operações em outro computador.
398. Cliente-servidor separa consumidores e fornecedores de serviços.
399. Peer-to-peer permite que participantes atuem de forma mais equivalente.
400. Computação em nuvem utiliza grandes conjuntos de recursos distribuídos.

---

# RESUMO FINAL PARA ENTENDER A MATÉRIA

401. Um Sistema Operacional administra os recursos do computador.
402. Esses recursos incluem CPU, memória, armazenamento e dispositivos.
403. O kernel é responsável por diversas funções fundamentais.
404. Os processos representam programas em execução.
405. As threads representam unidades de execução.
406. Processos podem executar concorrentemente.
407. Em máquinas multicore, tarefas podem executar em paralelo.
408. O escalonador organiza a utilização da CPU.
409. Sincronização evita conflitos entre tarefas.
410. Mutex e semáforos são mecanismos de sincronização.
411. Condições de corrida podem gerar resultados incorretos.
412. Deadlocks podem impedir o progresso dos processos.
413. A segurança protege o sistema contra acessos indevidos.
414. Autenticação identifica usuários.
415. Autorização define o que cada usuário pode fazer.
416. O menor privilégio limita os danos de possíveis ataques.
417. A proteção de memória impede acessos indevidos entre processos.
418. O modo usuário limita o acesso das aplicações.
419. O modo kernel permite operações privilegiadas.
420. Sistemas multimídia possuem necessidades específicas de desempenho.
421. Áudio e vídeo precisam ser processados continuamente.
422. Buffers ajudam a evitar interrupções durante streaming.
423. Latência pode prejudicar aplicações interativas.
424. Jitter representa variações na latência.
425. Sistemas de tempo real precisam respeitar prazos.
426. O deadline representa o prazo máximo de uma tarefa.
427. O escalonamento de tempo real considera prioridades e prazos.
428. Sistemas móveis precisam administrar energia.
429. Processadores móveis podem ajustar frequência para economizar energia.
430. Aplicativos móveis precisam de mecanismos de isolamento.
431. Permissões controlam o acesso aos recursos.
432. Sistemas distribuídos possuem vários computadores conectados.
433. A comunicação entre máquinas ocorre pela rede.
434. Redes introduzem latência e possibilidade de falhas.
435. Replicação pode melhorar a disponibilidade.
436. Sistemas distribuídos precisam lidar com consistência.
437. RPC facilita a comunicação entre programas em máquinas diferentes.
438. Balanceamento de carga distribui tarefas entre recursos.
439. Escalabilidade permite aumentar a capacidade do sistema.
440. Sistemas distribuídos são fundamentais para serviços de grande escala.

---

# MAPA MENTAL DOS CAPÍTULOS 8 A 13

```text
SISTEMAS OPERACIONAIS
│
├── CAP. 8 — MULTIPROCESSADORES
│   ├── Vários processadores
│   ├── Multicore
│   ├── Paralelismo
│   ├── Escalonamento
│   ├── Sincronização
│   └── Balanceamento de carga
│
├── CAP. 9 — SEGURANÇA
│   ├── Autenticação
│   ├── Autorização
│   ├── Permissões
│   ├── Menor privilégio
│   ├── Criptografia
│   └── Malware
│
├── CAP. 10 — MULTIMÍDIA
│   ├── Áudio
│   ├── Vídeo
│   ├── Streaming
│   ├── Buffer
│   ├── Latência
│   └── DMA
│
├── CAP. 11 — TEMPO REAL
│   ├── Deadline
│   ├── Prioridade
│   ├── Previsibilidade
│   ├── Tarefas periódicas
│   └── Escalonamento
│
├── CAP. 12 — DISPOSITIVOS MÓVEIS
│   ├── Smartphones
│   ├── Energia
│   ├── Memória
│   ├── Permissões
│   ├── Segurança
│   └── Comunicação sem fio
│
└── CAP. 13 — SISTEMAS DISTRIBUÍDOS
    ├── Vários computadores
    ├── Rede
    ├── Cliente-servidor
    ├── Peer-to-peer
    ├── Replicação
    ├── Consistência
    └── Computação em nuvem
```

# O QUE VOCÊ DEVE CONSEGUIR EXPLICAR

Ao terminar os capítulos 8 a 13, é importante conseguir responder:

1. O que é um sistema multiprocessador?
2. Qual é a diferença entre concorrência e paralelismo?
3. Por que a sincronização é necessária?
4. O que é uma condição de corrida?
5. O que é uma região crítica?
6. Para que servem mutex e semáforos?
7. O que é segurança em Sistemas Operacionais?
8. Qual é a diferença entre autenticação e autorização?
9. O que significa menor privilégio?
10. O que é malware?
11. Por que multimídia exige tratamento especial?
12. O que é streaming?
13. Para que serve um buffer?
14. O que são latência e jitter?
15. O que caracteriza um sistema de tempo real?
16. O que é um deadline?
17. Por que dispositivos móveis precisam controlar energia?
18. Por que aplicativos móveis precisam de permissões?
19. O que é um sistema distribuído?
20. Quais são os principais problemas de sistemas distribuídos?
21. O que é RPC?
22. O que é replicação?
23. O que é consistência?
24. O que é balanceamento de carga?
25. Como todos esses conceitos se relacionam com o Sistema Operacional?

# CONCLUSÃO

Os capítulos 8 a 13 mostram que os Sistemas Operacionais precisam lidar com diferentes tipos de computadores e diferentes necessidades.

Em sistemas multiprocessadores, o desafio é utilizar vários processadores de maneira eficiente e sincronizada.

Em segurança, o objetivo é proteger usuários, processos, arquivos e dispositivos.

Em multimídia, o sistema precisa trabalhar com grandes quantidades de dados e requisitos de tempo.

Em sistemas de tempo real, cumprir prazos é fundamental.

Em dispositivos móveis, o gerenciamento de energia, segurança e recursos possui grande importância.

Em sistemas distribuídos, vários computadores precisam trabalhar em conjunto utilizando redes de comunicação.

Apesar das diferenças, todos esses ambientes dependem de conceitos fundamentais de Sistemas Operacionais, como **processos, threads, memória, escalonamento, sincronização, Entrada/Saída, segurança e gerenciamento de recursos**.

A principal ideia é:

> **O Sistema Operacional funciona como um gerenciador que controla e organiza os recursos de hardware e software para que as aplicações possam funcionar de maneira eficiente, segura e organizada.**
