<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso Completo de Tecnologia da Informação - Leandro Bueno Style</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
            padding-bottom: 500px;
        }
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        nav {
            background-color: #343a40;
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffc107;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }
        .section {
            margin-bottom: 50px;
            padding: 30px;
            border-left: 5px solid #007bff;
            background-color: #f8f9fa;
        }
        h1, h2, h3, h4 {
            color: #007bff;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }
        h2 {
            font-size: 2.2em;
            border-bottom: 3px solid #007bff;
            padding-bottom: 15px;
            margin-top: 40px;
        }
        h3 {
            font-size: 1.8em;
            margin-top: 30px;
        }
        h4 {
            font-size: 1.4em;
            margin-top: 20px;
        }
        p {
            margin-bottom: 20px;
        }
        .code {
            background-color: #2d3748;
            color: #e2e8f0;
            padding: 15px;
            border-radius: 5px;
            font-family: 'Courier New', monospace;
            margin: 15px 0;
            overflow-x: auto;
            white-space: pre-wrap;
        }
        .example {
            background-color: #e9ecef;
            padding: 20px;
            border-radius: 5px;
            margin: 20px 0;
            border: 1px solid #dee2e6;
        }
        ul, ol {
            margin-left: 30px;
        }
        li {
            margin-bottom: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 25px 0;
            box-shadow: 0 2px 3px rgba(0,0,0,0.1);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 15px;
            text-align: left;
        }
        th {
            background-color: #007bff;
            color: white;
            font-weight: bold;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        .highlight {
            background-color: #fff3cd;
            padding: 15px;
            border: 1px solid #ffeaa7;
            border-radius: 5px;
            margin: 20px 0;
        }
        .warning {
            background-color: #f8d7da;
            color: #721c24;
            padding: 15px;
            border: 1px solid #f5c6cb;
            border-radius: 5px;
            margin: 20px 0;
        }
        .tip {
            background-color: #d1ecf1;
            color: #0c5460;
            padding: 15px;
            border: 1px solid #bee5eb;
            border-radius: 5px;
            margin: 20px 0;
        }
        img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 20px 0;
        }
        .image-caption {
            font-size: 0.9em;
            color: #666;
            text-align: center;
            margin-bottom: 20px;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 50px;
        }
        .module {
            border: 2px solid #007bff;
            border-radius: 10px;
            padding: 20px;
            margin: 30px 0;
        }
        .module h2 {
            margin-top: 0;
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5em;
            }
            h2 {
                font-size: 2em;
            }
            .container {
                padding: 10px;
            }
            .section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Curso Completo de Tecnologia da Informação</h1>
        <p>Aprenda T.I do básico ao avançado - Estilo Leandro Bueno</p>
    </header>

    <nav>
        <a href="#intro">Introdução</a>
        <a href="#hardware">Hardware</a>
        <a href="#software">Software</a>
        <a href="#redes">Redes</a>
        <a href="#seguranca">Segurança</a>
        <a href="#manutencao">Manutenção</a>
        <a href="#projetos">Projetos</a>
    </nav>

    <div class="container">
        <section id="intro" class="section">
            <h2>Introdução à Tecnologia da Informação</h2>
            <p>Bem-vindo ao curso completo de Tecnologia da Informação! Neste curso, vamos explorar desde os conceitos básicos até tópicos avançados, explicando cada componente, cabo e peça do mundo da computação.</p>
            <div class="highlight">
                <strong>O que é T.I?</strong> Tecnologia da Informação engloba tudo relacionado ao processamento, armazenamento e transmissão de dados digitais.
            </div>
            <h3>Hardware vs Software</h3>
            <p>No computador, temos duas partes principais:</p>
            <ul>
                <li><strong>Hardware:</strong> As peças físicas do computador (placa-mãe, processador, memória, etc.)</li>
                <li><strong>Software:</strong> Os programas e sistemas operacionais que fazem o hardware funcionar</li>
            </ul>
            <p>Sem software, o hardware não funciona, e vice-versa. Um exemplo de software é o Windows 11 ou Linux.</p>
        </section>

        <div id="hardware" class="module">
            <h2>Módulo 1: Hardware do Computador</h2>
            <section class="section">
                <h3>1.1 A Fonte de Alimentação</h3>
                <p>A fonte de alimentação é o coração do computador. Sua função básica é transformar energia elétrica alternada (AC) em corrente contínua (DC).</p>
                <img src="img/TI AJUSTADA.png" alt="Diagrama da fonte de alimentação">
                <p class="image-caption">Figura 1: Componentes internos de uma fonte de alimentação</p>
                <h4>Funções da Fonte:</h4>
                <ul>
                    <li>Transformar corrente alternada em contínua</li>
                    <li>Filtrar e estabilizar a corrente</li>
                    <li>Gerar tensões específicas: 3.3V, 5V e 12V</li>
                    <li>Proteger contra sobrecargas e curtos-circuitos</li>
                </ul>
                <h4>Tipos de Fontes:</h4>
                <ul>
                    <li><strong>Fonte Real (80 Plus):</strong> Aproveita 85% da energia, perde apenas 15% em calor</li>
                    <li><strong>Fonte Nominal:</strong> Aproveita 65%, perde 35% em calor</li>
                </ul>
                <div class="tip">
                    <strong>Dica:</strong> Sempre escolha fontes certificadas 80 Plus para maior eficiência energética.
                </div>
            </section>

            <section class="section">
                <h3>1.2 A Placa-Mãe (Motherboard)</h3>
                <img src="img/PLACA MÃE.png" alt="Diagrama da placa-mãe">
                <p class="image-caption">Figura 2: Componentes de uma placa-mãe</p>
                <p>A placa-mãe é como o sistema nervoso central do computador. Ela conecta todos os componentes e permite a comunicação entre eles.</p>
                <h4>Componentes Principais da Placa-Mãe:</h4>
                <ul>
                    <li><strong>Socket do Processador:</strong> Onde o CPU é instalado</li>
                    <li><strong>Slots de RAM:</strong> Para memória RAM</li>
                    <li><strong>Chipset:</strong> Controla a comunicação entre componentes</li>
                    <li><strong>Slots PCI/PCIe:</strong> Para placas de vídeo, som, etc.</li>
                    <li><strong>Conectores SATA:</strong> Para HDs e SSDs</li>
                    <li><strong>Conectores de Energia:</strong> 24-pin e 4/8-pin para CPU</li>
                </ul>
                <h4>Tipos de Placas-Mãe:</h4>
                <ul>
                    <li><strong>ATX:</strong> Padrão mais comum, tamanho médio</li>
                    <li><strong>Micro-ATX:</strong> Menor, para PCs compactos</li>
                    <li><strong>Mini-ITX:</strong> Muito pequena, para HTPCs</li>
                </ul>
            </section>

            <section class="section">
                <h3>1.3 O Processador (CPU)</h3>
                <img src="img/cpu.jpg" alt="Processador Intel ou AMD">
                <p class="image-caption">Figura 3: Exemplo de processador moderno</p>
                <p>O processador é o "cérebro" do computador. Ele executa todas as instruções e cálculos.</p>
                <h4>Partes do Processador:</h4>
                <ul>
                    <li><strong>Núcleos (Cores):</strong> Unidades de processamento independentes</li>
                    <li><strong>Threads:</strong> Capacidade de executar múltiplas tarefas simultaneamente</li>
                    <li><strong>Cache:</strong> Memória rápida integrada (L1, L2, L3)</li>
                    <li><strong>Frequência:</strong> Velocidade medida em GHz</li>
                </ul>
                <h4>Como Funciona:</h4>
                <p>O CPU busca instruções na memória, decodifica, executa e armazena resultados. Este ciclo é chamado de "ciclo de busca-decodificação-execução".</p>
                <div class="example">
                    <p>Um processador quad-core com 8 threads pode executar 8 tarefas simultaneamente, melhorando o desempenho em multitarefas.</p>
                </div>
            </section>

            <section class="section">
                <h3>1.4 Memória RAM</h3>
                <img src="img/ram.jpg" alt="Módulo de memória RAM DDR4">
                <p class="image-caption">Figura 4: Módulo de RAM DDR4</p>
                <p>A RAM (Random Access Memory) é a memória de trabalho do computador. Ela armazena dados temporariamente para acesso rápido.</p>
                <h4>Tipos de RAM:</h4>
                <ul>
                    <li><strong>DDR3:</strong> Mais antiga, velocidade até 2133 MHz</li>
                    <li><strong>DDR4:</strong> Atual padrão, até 3200 MHz ou mais</li>
                    <li><strong>DDR5:</strong> Nova geração, ainda mais rápida</li>
                </ul>
                <h4>Como Funciona:</h4>
                <p>A RAM é volátil - perde dados quando o PC desliga. Ela trabalha em conjunto com o processador para executar programas.</p>
                <div class="tip">
                    <strong>Dica:</strong> Para jogos e edição de vídeo, quanto mais RAM melhor. Mínimo recomendado: 8GB.</div>
            </section>

            <section class="section">
                <h3>1.5 Armazenamento: HD e SSD</h3>
                <img src="img/hd_ssd.jpg" alt="HD e SSD lado a lado">
                <p class="image-caption">Figura 5: Comparação entre HD (esquerda) e SSD (direita)</p>
                <h4>Disco Rígido (HD):</h4>
                <ul>
                    <li>Armazenamento magnético em pratos giratórios</li>
                    <li>Capacidades grandes e baratas</li>
                    <li>Velocidade limitada pelos discos (5400/7200 RPM)</li>
                    <li>Ruído e calor gerados</li>
                </ul>
                <h4>SSD (Solid State Drive):</h4>
                <ul>
                    <li>Armazenamento em chips de memória flash</li>
                    <li>Muito mais rápido que HDs</li>
                    <li>Silencioso e resistente a choques</li>
                    <li>Mais caro por GB</li>
                </ul>
                <h4>Conectores:</h4>
                <ul>
                    <li><strong>SATA:</strong> Padrão antigo, velocidade até 6 Gb/s</li>
                    <li><strong>M.2:</strong> Conector moderno, integrado à placa-mãe</li>
                    <li><strong>NVMe:</strong> Protocolo rápido para SSDs M.2</li>
                </ul>
            </section>

            <section class="section">
                <h3>1.6 Placa de Vídeo (GPU)</h3>
                <img src="img/gpu.jpg" alt="Placa de vídeo dedicada">
                <p class="image-caption">Figura 6: Placa de vídeo NVIDIA ou AMD</p>
                <p>A GPU processa gráficos e imagens. Essencial para jogos, edição de vídeo e tarefas gráficas intensas.</p>
                <h4>Componentes:</h4>
                <ul>
                    <li><strong>GPU (Unidade de Processamento Gráfico):</strong> O processador dedicado</li>
                    <li><strong>VRAM:</strong> Memória dedicada da placa de vídeo</li>
                    <li><strong>Cooler:</strong> Sistema de refrigeração</li>
                    <li><strong>Conectores:</strong> HDMI, DisplayPort, DVI</li>
                </ul>
                <h4>Integrada vs Dedicada:</h4>
                <ul>
                    <li><strong>Integrada:</strong> Parte do processador, usa RAM do sistema</li>
                    <li><strong>Dedicada:</strong> Placa separada com VRAM própria</li>
                </ul>
            </section>

            <section class="section">
                <h3>1.7 Gabinete e Refrigeração</h3>
                <h4>Gabinete (Case):</h4>
                <ul>
                    <li>Protege componentes internos</li>
                    <li>Fornece fluxo de ar</li>
                    <li>Suporta diferentes formatos (ATX, Micro-ATX)</li>
                    <li>Inclui fans para refrigeração</li>
                </ul>
                <h4>Sistema de Refrigeração:</h4>
                <ul>
                    <li><strong>Air Cooling:</strong> Fans e heatsinks</li>
                    <li><strong>Liquid Cooling:</strong> Sistema fechado com água</li>
                    <li><strong>Thermal Paste:</strong> Condutor de calor entre CPU e cooler</li>
                </ul>
            </section>

            <section class="section">
                <h3>1.8 Cabos e Conectores</h3>
                <p>Vamos detalhar os cabos mais importantes do computador:</p>
                <h4>Cabo de Energia da Placa-Mãe (24-pin):</h4>
                <ul>
                    <li>Conecta fonte à placa-mãe</li>
                    <li>Fornece energia principal (3.3V, 5V, 12V)</li>
                    <li>24 pinos divididos em duas seções</li>
                </ul>
                <h4>Cabo de Energia do Processador (4/8-pin):</h4>
                <ul>
                    <li>Alimenta diretamente o CPU</li>
                    <li>4-pin para processadores básicos</li>
                    <li>8-pin para processadores de alto desempenho</li>
                </ul>
                <h4>Cabo SATA:</h4>
                <ul>
                    <li>Conecta HDs e SSDs à placa-mãe</li>
                    <li>Transmite dados e energia</li>
                    <li>Velocidade até 6 Gb/s</li>
                </ul>
                <h4>Cabo PCIe:</h4>
                <ul>
                    <li>Para placas de vídeo e outros dispositivos</li>
                    <li>6/8/16 pinos dependendo da potência</li>
                    <li>Alimenta GPUs de alto desempenho</li>
                </ul>
                <div class="warning">
                    <strong>Atenção:</strong> Nunca force um cabo no conector errado. Verifique os pinos e formatos.
                </div>
            </section>
        </div>

        <div id="software" class="module">
            <h2>Módulo 2: Software e Sistemas Operacionais</h2>
            <section class="section">
                <h3>2.1 O que é Software</h3>
                <p>Software são programas e instruções que fazem o hardware funcionar. Sem software, o computador é apenas uma caixa inerte.</p>
                <h4>Tipos de Software:</h4>
                <ul>
                    <li><strong>Sistema Operacional:</strong> Interface entre usuário e hardware</li>
                    <li><strong>Aplicativos:</strong> Programas para tarefas específicas</li>
                    <li><strong>Drivers:</strong> Permitem comunicação com hardware</li>
                    <li><strong>Firmware:</strong> Software embutido em dispositivos</li>
                </ul>
            </section>

            <section class="section">
                <h3>2.2 Sistemas Operacionais</h3>
                <h4>Windows:</h4>
                <ul>
                    <li>Mais usado no mundo</li>
                    <li>Interface gráfica intuitiva</li>
                    <li>Compatível com maioria dos softwares</li>
                    <li>Versões: Home, Pro, Enterprise</li>
                </ul>
                <h4>Linux:</h4>
                <ul>
                    <li>Gratuito e open-source</li>
                    <li>Altamente customizável</li>
                    <li>Distribuições: Ubuntu, Fedora, CentOS</li>
                    <li>Usado em servidores e desenvolvimento</li>
                </ul>
                <h4>macOS:</h4>
                <ul>
                    <li>Exclusivo para Macs</li>
                    <li>Interface elegante</li>
                    <li>Integração perfeita com hardware Apple</li>
                </ul>
            </section>

            <section class="section">
                <h3>2.3 Como o Sistema Operacional Funciona</h3>
                <p>O SO gerencia recursos do computador:</p>
                <ul>
                    <li><strong>Gerenciamento de Memória:</strong> Aloca RAM para programas</li>
                    <li><strong>Gerenciamento de Processos:</strong> Executa e controla programas</li>
                    <li><strong>Sistema de Arquivos:</strong> Organiza dados no armazenamento</li>
                    <li><strong>Drivers:</strong> Comunicação com dispositivos</li>
                    <li><strong>Interface:</strong> Permite interação com usuário</li>
                </ul>
            </section>
        </div>

        <div id="redes" class="module">
            <h2>Módulo 3: Redes de Computadores</h2>
            <section class="section">
                <h3>3.1 Conceitos Básicos de Rede</h3>
                <p>Uma rede de computadores conecta dispositivos para compartilhar recursos e informações.</p>
                <h4>Componentes de uma Rede:</h4>
                <ul>
                    <li><strong>Dispositivos:</strong> Computadores, smartphones, etc.</li>
                    <li><strong>Meio de Transmissão:</strong> Cabos, Wi-Fi, fibra óptica</li>
                    <li><strong>Dispositivos de Rede:</strong> Roteadores, switches, modems</li>
                    <li><strong>Protocolos:</strong> Regras de comunicação</li>
                </ul>
            </section>

            <section class="section">
                <h3>3.2 Cabos de Rede</h3>
                <img src="img/cabo_rede.jpg" alt="Cabo de rede UTP">
                <p class="image-caption">Figura 7: Cabo de rede Ethernet UTP</p>
                <h4>Cabo UTP (Par Trançado):</h4>
                <ul>
                    <li>Mais comum em redes locais</li>
                    <li>Categorias: Cat5, Cat5e, Cat6, Cat6a</li>
                    <li>Velocidades: 100 Mb/s a 10 Gb/s</li>
                    <li>Distância máxima: 100 metros</li>
                </ul>
                <h4>Cabo Coaxial:</h4>
                <ul>
                    <li>Usado em TV a cabo e internet</li>
                    <li>Conector BNC ou F-type</li>
                    <li>Menos suscetível a interferências</li>
                </ul>
                <h4>Fibra Óptica:</h4>
                <ul>
                    <li>Transmissão por luz</li>
                    <li>Velocidades muito altas</li>
                    <li>Distâncias maiores</li>
                    <li>Mais cara e frágil</li>
                </ul>
            </section>

            <section class="section">
                <h3>3.3 Dispositivos de Rede</h3>
                <img src="img/roteador.jpg" alt="Roteador Wi-Fi">
                <p class="image-caption">Figura 8: Roteador wireless moderno</p>
                <h4>Roteador:</h4>
                <ul>
                    <li>Conecta redes diferentes</li>
                    <li>Direciona tráfego de dados</li>
                    <li>Atribui endereços IP</li>
                    <li>Fornece Wi-Fi</li>
                </ul>
                <h4>Switch:</h4>
                <img src="img/switch.jpg" alt="Switch de rede">
                <p class="image-caption">Figura 9: Switch Ethernet para rede local</p>
                <ul>
                    <li>Conecta dispositivos na mesma rede</li>
                    <li>Cria conexões dedicadas</li>
                    <li>Melhora performance da rede</li>
                </ul>
                <h4>Modem:</h4>
                <ul>
                    <li>Conecta à internet</li>
                    <li>Converte sinais digitais/analógicos</li>
                    <li>Tipos: DSL, cabo, fibra, 4G/5G</li>
                </ul>
            </section>

            <section class="section">
                <h3>3.4 Protocolos de Rede</h3>
                <h4>TCP/IP:</h4>
                <ul>
                    <li>Protocolo fundamental da internet</li>
                    <li>TCP: Transmissão confiável</li>
                    <li>IP: Endereçamento de dispositivos</li>
                </ul>
                <h4>HTTP/HTTPS:</h4>
                <ul>
                    <li>Protocolos web</li>
                    <li>HTTP: Não criptografado</li>
                    <li>HTTPS: Criptografado (seguro)</li>
                </ul>
                <h4>DNS:</h4>
                <ul>
                    <li>Traduz nomes de domínio em IPs</li>
                    <li>Como uma lista telefônica da internet</li>
                </ul>
            </section>
        </div>

        <div id="seguranca" class="module">
            <h2>Módulo 4: Segurança da Informação</h2>
            <section class="section">
                <h3>4.1 Conceitos de Segurança</h3>
                <p>Segurança da informação protege dados contra ameaças.</p>
                <h4>Pilares da Segurança:</h4>
                <ul>
                    <li><strong>Confidencialidade:</strong> Apenas autorizados acessam</li>
                    <li><strong>Integridade:</strong> Dados não alterados indevidamente</li>
                    <li><strong>Disponibilidade:</strong> Acesso quando necessário</li>
                </ul>
            </section>

            <section class="section">
                <h3>4.2 Ameaças Comuns</h3>
                <ul>
                    <li><strong>Vírus:</strong> Programas maliciosos que se replicam</li>
                    <li><strong>Trojan:</strong> Parecem legítimos mas são maliciosos</li>
                    <li><strong>Ransomware:</strong> Criptografa arquivos e pede resgate</li>
                    <li><strong>Phishing:</strong> Engana usuário para obter dados</li>
                    <li><strong>Malware:</strong> Software malicioso em geral</li>
                </ul>
            </section>

            <section class="section">
                <h3>4.3 Proteções Básicas</h3>
                <img src="img/antivirus.jpg" alt="Software antivírus">
                <p class="image-caption">Figura 10: Interface de software antivírus</p>
                <ul>
                    <li><strong>Antivírus:</strong> Detecta e remove malware</li>
                    <li><strong>Firewall:</strong> Bloqueia acessos não autorizados</li>
                    <li><strong>Atualizações:</strong> Mantém software seguro</li>
                    <li><strong>Senhas Fortes:</strong> Dificultam invasões</li>
                    <li><strong>Backup:</strong> Cópias de segurança dos dados</li>
                </ul>
            </section>
        </div>

        <div id="manutencao" class="module">
            <h2>Módulo 5: Manutenção e Serviços Básicos</h2>
            <section class="section">
                <h3>5.1 Montagem de Computador</h3>
                <img src="img/montagem_pc.jpg" alt="Montagem de computador">
                <p class="image-caption">Figura 12: Processo de montagem de um PC desktop</p>
                <p>Aprender a montar um computador é uma habilidade essencial para profissionais de T.I. Aqui está o passo a passo completo com imagens ilustrativas:</p>
                
                <h4>Passo 1: Preparação</h4>
                <img src="img/gabinete_aberto.jpg" alt="Gabinete aberto mostrando interior vazio">
                <p class="image-caption">Figura 13: Gabinete aberto pronto para montagem</p>
                <div class="highlight">
                    <strong>Gabinete (Case):</strong> Protege componentes, fornece fluxo de ar, suporta placas-mãe ATX/Micro-ATX. Utilidade: Organização, refrigeração, redução de ruído. Conecta: Todos os componentes internos.
                </div>
                <ul>
                    <li>Reúna todos os componentes: gabinete, placa-mãe, processador, cooler, RAM, SSD/HD, fonte, placa de vídeo</li>
                    <li>Prepare uma superfície antiestática (use pulseira antiestática)</li>
                    <li>Tenha ferramentas: chave de fenda Phillips, alicate para cabos</li>
                </ul>
                
                <h4>Passo 2: Instalação da Placa-Mãe</h4>
                <img src="img/instalando_cpu.jpg" alt="Instalando processador na placa-mãe">
                <p class="image-caption">Figura 14: Instalação do processador no socket</p>
                <div class="highlight">
                    <strong>Processador (CPU):</strong> "Cérebro" do PC, executa cálculos e instruções. Utilidade: Processamento de dados, multitarefas. Conecta: Socket LGA/AM4 da placa-mãe. Importante: Nunca toque nos pinos!
                </div>
                <ul>
                    <li>Instale o processador no socket (cuidado com os pinos!)</li>
                    <li>Aplique pasta térmica no processador</li>
                    <li>Instale o cooler do processador</li>
                    <li>Coloque a placa-mãe no gabinete e parafus</li>
                </ul>
                <img src="img/instalando_cooler.jpg" alt="Instalando cooler no processador">
                <p class="image-caption">Figura 15: Instalação do cooler com pasta térmica</p>
                <div class="highlight">
                    <strong>Cooler/Refrigeração:</strong> Dissipa calor do CPU/GPU. Utilidade: Previne superaquecimento, aumenta vida útil. Conecta: Socket do processador ou placa-mãe. Tipos: Air cooling (fans) ou Liquid cooling (água).
                </div>
                
                <h4>Passo 3: Memória RAM e Armazenamento</h4>
                <img src="img/instalando_ram.jpg" alt="Instalando módulos de RAM">
                <p class="image-caption">Figura 16: Instalação da memória RAM nos slots</p>
                <div class="highlight">
                    <strong>Memória RAM:</strong> Memória temporária de trabalho. Utilidade: Armazenamento rápido de dados em uso, multitarefas. Conecta: Slots DDR4 na placa-mãe. Capacidade típica: 8-32GB. Velocidade: 3200MHz+.
                </div>
                <ul>
                    <li>Instale os módulos de RAM nos slots (geralmente coloridos)</li>
                    <li>Instale SSD M.2 na placa-mãe ou HD/SATA no compartimento</li>
                    <li>Conecte cabos SATA se necessário</li>
                </ul>
                <img src="img/instalando_ssd.jpg" alt="Instalando SSD no gabinete">
                <p class="image-caption">Figura 17: Instalação do SSD no compartimento do gabinete</p>
                <div class="highlight">
                    <strong>SSD (Solid State Drive):</strong> Armazenamento rápido sem partes móveis. Utilidade: Inicialização rápida do sistema, carregamento de programas. Conecta: M.2 na placa-mãe ou SATA. Velocidade: 500MB/s+ (NVMe). Capacidade: 500GB-2TB+.
                </div>
                <div class="tip">
                    <strong>HD vs SSD:</strong> HD é mais barato e maior capacidade, mas mais lento e ruidoso. SSD é mais rápido e silencioso, ideal para sistema operacional.
                </div>
                
                <h4>Passo 4: Placa de Vídeo e Conectores</h4>
                <img src="img/instalando_gpu.jpg" alt="Instalando placa de vídeo">
                <p class="image-caption">Figura 18: Instalação da placa de vídeo no slot PCIe</p>
                <div class="highlight">
                    <strong>Placa de Vídeo (GPU):</strong> Processa gráficos e imagens. Utilidade: Jogos, edição de vídeo, CAD. Conecta: Slot PCIe x16. VRAM: 4-8GB+. Interfaces: HDMI, DisplayPort, DVI.
                </div>
                <ul>
                    <li>Instale a GPU na placa-mãe (PCIe x16)</li>
                    <li>Conecte cabos de energia: 24-pin para placa-mãe, 8-pin para CPU, PCIe para GPU</li>
                    <li>Conecte cabos de dados: SATA para HDs</li>
                </ul>
                <img src="img/conectando_cabos.jpg" alt="Conectando cabos de energia">
                <p class="image-caption">Figura 19: Conexão dos cabos de energia e dados</p>
                <div class="highlight">
                    <strong>Cabos de Energia:</strong>
                    <ul>
                        <li><strong>24-pin (Placa-mãe):</strong> Energia principal (3.3V, 5V, 12V). Conecta: Placa-mãe à fonte.</li>
                        <li><strong>8-pin CPU:</strong> Energia dedicada ao processador. Conecta: Placa-mãe à fonte.</li>
                        <li><strong>6/8-pin PCIe:</strong> Energia para GPU. Conecta: Placa de vídeo à fonte.</li>
                        <li><strong>SATA:</strong> Energia + dados para HD/SSD. Conecta: Armazenamento à fonte e placa-mãe.</li>
                    </ul>
                </div>
                <div class="warning">
                    <strong>Importante:</strong> Nunca force conectores! Verifique pinos e formatos. Cabos errados podem danificar componentes.
                </div>
                
                <h4>Passo 5: Teste e Configuração</h4>
                <ul>
                    <li>Ligue o PC e entre na BIOS (geralmente Del ou F2)</li>
                    <li>Verifique se todos os componentes são detectados</li>
                    <li>Instale o sistema operacional</li>
                    <li>Instale drivers e atualizações</li>
                </ul>
                <div class="warning">
                    <strong>Cuidado:</strong> Descarregue eletricidade estática tocando em metal antes de manusear componentes. Nunca force conectores!
                </div>
                <div class="tip">
                    <strong>Dica Profissional:</strong> Organize os cabos com abraçadeiras para melhor fluxo de ar e aparência.
                </div>
                <h4>Componentes Essenciais - O que Cada um Faz</h4>
                <div class="highlight">
                    <strong>Fonte de Alimentação (PSU):</strong> Converte AC em DC. Utilidade: Fornece energia estável. Conecta: Todos os componentes. Certificação: 80 Plus Bronze+. Potência: 500-750W para PCs gamers.
                </div>
                <div class="highlight">
                    <strong>Placa-Mãe:</strong> Sistema nervoso central. Utilidade: Conecta todos os componentes. Chipset: Controla comunicação. Formatos: ATX, Micro-ATX. Soquetes: AM4 (AMD), LGA 1700 (Intel 12ª/13ª gen).
                </div>
                <div class="highlight">
                    <strong>Fans/Ventoinhas:</strong> Circulam ar. Utilidade: Refrigeração. Conecta: Headers da placa-mãe. Controle: PWM para velocidade variável.
                </div>
                <div class="highlight">
                    <strong>Conectores Front Panel:</strong> Botão power, LED, USB. Utilidade: Interface com o usuário. Conecta: Placa-mãe aos botões do gabinete.
                </div>
                <h4>Tabela Comparativa - Componentes Essenciais</h4>
                <table>
                    <thead>
                        <tr>
                            <th>Componente</th>
                            <th>Função Principal</th>
                            <th>Onde Conecta</th>
                            <th>Utilidade Prática</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Processador (CPU)</td>
                            <td>Executa cálculos e instruções</td>
                            <td>Socket da placa-mãe</td>
                            <td>Determina velocidade de processamento</td>
                        </tr>
                        <tr>
                            <td>Memória RAM</td>
                            <td>Armazenamento temporário</td>
                            <td>Slots DDR4</td>
                            <td>Multitarefas, velocidade de programas</td>
                        </tr>
                        <tr>
                            <td>SSD/HD</td>
                            <td>Armazenamento permanente</td>
                            <td>M.2 ou SATA</td>
                            <td>Guardar arquivos, sistema operacional</td>
                        </tr>
                        <tr>
                            <td>Placa de Vídeo</td>
                            <td>Processa gráficos</td>
                            <td>Slot PCIe x16</td>
                            <td>Jogos, edição de vídeo</td>
                        </tr>
                        <tr>
                            <td>Fonte</td>
                            <td>Fornece energia</td>
                            <td>Todos os componentes</td>
                            <td>Alimentação elétrica estável</td>
                        </tr>
                        <tr>
                            <td>Placa-Mãe</td>
                            <td>Conecta componentes</td>
                            <td>Gabinete</td>
                            <td>Comunicação entre peças</td>
                        </tr>
                    </tbody>
                </table>
                <h4>Problemas Comuns na Montagem e Soluções</h4>
                <div class="warning">
                    <strong>PC não liga:</strong> Verifique conexões de energia (24-pin, 8-pin CPU). Teste fonte em outro PC. Cheque botão power do gabinete.
                </div>
                <div class="warning">
                    <strong>Beeps na inicialização:</strong> Beeps indicam problemas. 1 beep = OK. Beeps longos = RAM. Beeps curtos repetidos = placa-mãe.
                </div>
                <div class="warning">
                    <strong>Tela preta:</strong> Verifique cabo de vídeo na GPU (não na placa-mãe integrada). Teste monitor em outro PC.
                </div>
                <div class="warning">
                    <strong>Componente não detectado:</strong> Verifique conexões. Reinicie CMOS (jumper na placa-mãe). Atualize BIOS se necessário.
                </div>
                <div class="tip">
                    <strong>Ferramentas Essenciais:</strong> Multímetro para testar voltagens, chave de fenda, pinça antiestática, pasta térmica extra.
                </div>
                <h4>Compatibilidade de Componentes</h4>
                <div class="highlight">
                    <strong>Verificações Importantes:</strong>
                    <ul>
                        <li><strong>Socket CPU:</strong> AM4 para Ryzen, LGA 1700 para Intel 12ª/13ª gen</li>
                        <li><strong>RAM:</strong> DDR4 para maioria dos PCs atuais</li>
                        <li><strong>Placa-mãe:</strong> Chipset deve suportar CPU (B450 para Ryzen, B660 para Intel)</li>
                        <li><strong>Fonte:</strong> Potência suficiente (CPU + GPU + 100W overhead)</li>
                        <li><strong>Gabinete:</strong> Deve suportar formato da placa-mãe</li>
                    </ul>
                </div>
                <div class="tip">
                    <strong>Sites Úteis:</strong> PCPartPicker.com para verificar compatibilidade. Sempre pesquise reviews antes de comprar.
                </div>
            </section>

            <section class="section">
                <h3>5.2 Reparo de Celulares - Troca de Tela</h3>
                <img src="img/troca_tela_celular.jpg" alt="Troca de tela de celular">
                <p class="image-caption">Figura 13: Reparo de tela quebrada em smartphone</p>
                <p>A troca de tela é um dos reparos mais comuns em celulares. Requer ferramentas específicas e cuidado.</p>
                <h4>Ferramentas Necessárias:</h4>
                <ul>
                    <li>Kit de abertura de celular (spudger, sucção de tela)</li>
                    <li>Aquecedor de iOpener ou secador de cabelo</li>
                    <li>Chaves de precisão (Phillips e Torx)</li>
                    <li>Tela de reposição compatível</li>
                    <li>Adesivo para tela (cola)</li>
                </ul>
                <h4>Passo a Passo da Troca:</h4>
                <ol>
                    <li><strong>Desligue o celular</strong> e remova SIM card e cartão SD</li>
                    <li><strong>Aqueça a tela</strong> por 2-3 minutos para amolecer a cola</li>
                    <li><strong>Levante a tela</strong> usando sucção e spudger (comece pelo canto)</li>
                    <li><strong>Desconecte o flex</strong> da tela quebrada (cuidado com conectores)</li>
                    <li><strong>Remova a tela antiga</strong> e limpe resíduos de cola</li>
                    <li><strong>Instale a nova tela</strong> conectando o flex e posicionando</li>
                    <li><strong>Aplique cola</strong> ao redor da borda e pressione por 30 minutos</li>
                    <li><strong>Teste</strong> a tela antes de fechar completamente</li>
                </ol>
                <div class="tip">
                    <strong>Dica:</strong> Pratique em celulares velhos primeiro. Modelos diferentes têm técnicas ligeiramente diferentes.
                </div>
                <h4>Modelos Comuns:</h4>
                <ul>
                    <li>iPhone: Use ferramentas especiais da Apple</li>
                    <li>Samsung: Telas AMOLED, cuidado com dobras</li>
                    <li>Motorola/Xiaomi: Geralmente mais fáceis de reparar</li>
                </ul>
            </section>

            <section class="section">
                <h3>5.3 Serviços Básicos de Manutenção</h3>
                <h4>Limpeza de Computador</h4>
                <img src="img/limpeza_pc.jpg" alt="Limpeza interna de PC">
                <p class="image-caption">Figura 14: Limpeza de poeira em componentes internos</p>
                <ul>
                    <li><strong>Externa:</strong> Limpe teclado, mouse e monitor com pano microfiber</li>
                    <li><strong>Interna:</strong> Use ar comprimido para remover poeira de fans e heatsinks</li>
                    <li><strong>Frequência:</strong> A cada 3-6 meses para desktops, 6-12 meses para notebooks</li>
                    <li><strong>Benefícios:</strong> Melhora refrigeração, reduz ruído, aumenta vida útil</li>
                </ul>
                <h4>Troca de Bateria de Notebook</h4>
                <ul>
                    <li>Identifique o modelo da bateria (geralmente no fundo do notebook)</li>
                    <li>Desligue e desconecte da energia</li>
                    <li>Remova parafusos e conector da bateria</li>
                    <li>Instale a nova bateria e recoloque os parafusos</li>
                    <li>Calibre a bateria carregando completamente e descarregando</li>
                </ul>
                <h4>Formatação e Reinstalação</h4>
                <ul>
                    <li><strong>Backup:</strong> Salve dados importantes antes</li>
                    <li><strong>Boot USB:</strong> Crie mídia de instalação do Windows/Linux</li>
                    <li><strong>Particionamento:</strong> Configure discos durante instalação</li>
                    <li><strong>Drivers:</strong> Instale drivers específicos do hardware</li>
                    <li><strong>Programas:</strong> Reinstale software necessário</li>
                </ul>
                <h4>Diagnóstico de Problemas</h4>
                <ul>
                    <li><strong>Não liga:</strong> Verifique fonte, cabos, botão power</li>
                    <li><strong>Tela azul:</strong> Problemas de driver, RAM defeituosa</li>
                    <li><strong>Lento:</strong> Malware, disco cheio, falta de RAM</li>
                    <li><strong>Aquecimento:</strong> Limpeza, pasta térmica, fans</li>
                </ul>
            </section>

            <section class="section">
                <h3>5.4 Dicas de Segurança no Trabalho</h3>
                <ul>
                    <li><strong>Equipamentos de Proteção:</strong> Use luvas antiestáticas, óculos de proteção</li>
                    <li><strong>Organização:</strong> Mantenha workspace limpo e organizado</li>
                    <li><strong>Eletricidade:</strong> Desconecte aparelhos antes de abrir</li>
                    <li><strong>Certificações:</strong> Considere CompTIA A+ para profissionais</li>
                    <li><strong>Atualização:</strong> Mantenha-se atualizado com novas tecnologias</li>
                </ul>
            </section>
        </div>

        <section id="projetos" class="section">
            <h2>Projetos Práticos de T.I</h2>
            <h3>Projeto 1: Montagem Completa de PC</h3>
            <p>Monte um computador do zero seguindo o guia passo a passo. Documente cada etapa com fotos.</p>
            <h3>Projeto 2: Reparo de Smartphone</h3>
            <p>Pratique troca de tela em um celular velho ou doado. Aprenda técnicas de desmontagem segura.</p>
            <h3>Projeto 3: Manutenção Preventiva</h3>
            <p>Realize limpeza completa e manutenção em 3 computadores diferentes.</p>
            <h3>Projeto 4: Rede Doméstica</h3>
            <p>Configure uma rede Wi-Fi segura para sua casa.</p>
            <h3>Projeto 5: Servidor Local</h3>
            <img src="img/servidor.jpg" alt="Servidor de dados">
            <p class="image-caption">Figura 11: Servidor para projetos locais</p>
            <p>Configure um servidor web local usando Apache ou Nginx.</p>
            <h3>Projeto 6: Backup Automático</h3>
            <p>Crie um sistema de backup automático para seus dados.</p>
            <div class="highlight">
                <strong>Próximos Passos:</strong> Com este conhecimento, você está pronto para trabalhar em suporte técnico, assistência técnica ou abrir seu próprio negócio de reparos.
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Curso de Tecnologia da Informação. Aprenda como um profissional!</p>
    </footer>
</body>
</html>
