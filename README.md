<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monzato – Ateliê de Bordados | Arte em Ponto Cruz</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primaria: #B5651D; /* Terracota */
            --secundaria: #84A98C; /* Verde Eucalipto */
            --fundo: #FAFAF5;
            --texto: #111827;
        }
        body { font-family: 'Inter', sans-serif; background-color: var(--fundo); color: var(--texto); scroll-behavior: smooth; }
        .glass { background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(10px); }
        .hero-gradient { background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1517430816045-df4b7de11d1d?q=80&w=1200'); background-size: cover; background-position: center; }
        .btn-whats { background-color: #25D366; transition: all 0.3s ease; }
        .btn-whats:hover { transform: translateY(-3px); box-shadow: 0 10px 15px -3px rgba(37, 211, 102, 0.4); }
        .card-produto:hover img { transform: scale(1.05); }
    </style>
</head>
<body>

    <nav class="fixed w-full z-50 glass border-b border-gray-200">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold tracking-tighter text-terracota">
                MONZATO <span class="text-sm font-light block">ATELIÊ DE BORDADOS</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#inicio" class="hover:text-amber-700">Início</a>
                <a href="#sobre" class="hover:text-amber-700">Sobre</a>
                <a href="#servicos" class="hover:text-amber-700">Serviços</a>
                <a href="#catalogo" class="hover:text-amber-700">Catálogo</a>
            </div>
            <a href="https://wa.me/5522998665130" class="btn-whats text-white px-6 py-2 rounded-full font-bold flex items-center">
                <i class="fab fa-whatsapp mr-2"></i> ORÇAMENTO
            </a>
        </div>
    </nav>

    <section id="inicio" class="hero-gradient h-screen flex items-center justify-center text-center text-white px-4">
        <div class="max-w-3xl">
            <span class="uppercase tracking-widest text-sm mb-4 block text-amber-200">Artesanato Exclusivo em Italva - RJ</span>
            <h2 class="text-5xl md:text-7xl font-extrabold mb-6 leading-tight">Bordados que contam a sua história.</h2>
            <p class="text-xl mb-8 opacity-90">A delicadeza do Ponto Cruz e a perfeição do avesso em peças únicas feitas com amor.</p>
            <div class="flex flex-col md:flex-row gap-4 justify-center">
                <a href="#catalogo" class="bg-white text-gray-900 px-8 py-4 rounded-lg font-bold hover:bg-amber-50 transition">Ver Coleção</a>
                <a href="https://wa.me/5522998665130" class="border-2 border-white px-8 py-4 rounded-lg font-bold hover:bg-white hover:text-gray-900 transition">Falar com a Artesã</a>
            </div>
        </div>
    </section>

    <section id="sobre" class="py-24 container mx-auto px-6">
        <div class="flex flex-col md:flex-row items-center gap-12">
            <div class="md:w-1/2">
                <img src="https://images.unsplash.com/photo-1605647540924-852290f6b0d5?q=80&w=800" class="rounded-2xl shadow-2xl" alt="Mãos bordando">
            </div>
            <div class="md:w-1/2">
                <h3 class="text-amber-700 font-bold mb-2 uppercase tracking-wide">Nossa Essência</h3>
                <h2 class="text-4xl font-bold mb-6 italic">O amor em cada ponto.</h2>
                <p class="text-gray-600 text-lg mb-6 leading-relaxed">
                    Localizado no coração de <strong>Italva</strong>, o Ateliê Monzato nasceu da paixão pela arte milenar do bordado. Cada peça que sai de nossas mãos carrega não apenas fios e tecidos, mas o tempo, a dedicação e o carinho necessários para tornar sua casa mais acolhedora ou seu presente inesquecível.
                </p>
                <div class="grid grid-cols-2 gap-6 mb-8">
                    <div>
                        <h4 class="font-bold text-xl text-amber-800">+100%</h4>
                        <p class="text-sm text-gray-500">Feito à Mão</p>
                    </div>
                    <div>
                        <h4 class="font-bold text-xl text-amber-800">Premium</h4>
                        <p class="text-sm text-gray-500">Avesso Perfeito</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="catalogo" class="py-24 bg-gray-50">
        <div class="container mx-auto px-6 text-center mb-16">
            <h2 class="text-4xl font-bold mb-4 italic text-amber-900">Nossa Vitrine de Encantos</h2>
            <p class="text-gray-600">Toque em cada peça para solicitar personalização via WhatsApp.</p>
        </div>

        <div class="container mx-auto px-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
            
            <div class="card-produto bg-white rounded-2xl overflow-hidden shadow-lg transition-all duration-300">
                <img src="https://i.postimg.cc/mD8D905X/passadeira-de-mesa.jpg" class="w-full h-80 object-cover transition-transform duration-500">
                <div class="p-6">
                    <h4 class="font-bold text-xl mb-2">Passadeira Real com Rosas</h4>
                    <p class="text-gray-500 text-sm mb-4 italic">Bordado Ponto Cruz com acabamento em renda luxo.</p>
                    <div class="flex justify-between items-center">
                        <span class="text-amber-700 font-bold">Sob Consulta</span>
                        <a href="https://wa.me/5522998665130?text=Ol%C3%A1!+Quero+saber+mais+sobre+a+Passadeira+de+Rosas" class="btn-whats text-white p-2 rounded-full px-4 text-xs font-bold">RESERVAR</a>
                    </div>
                </div>
            </div>

            <div class="card-produto bg-white rounded-2xl overflow-hidden shadow-lg">
                <img src="https://i.postimg.cc/dV7mN3xX/toalha-de-bebe-com-nome-da-crianca.jpg" class="w-full h-80 object-cover transition-transform duration-500">
                <div class="p-6">
                    <h4 class="font-bold text-xl mb-2">Toalha Infantil Personalizada</h4>
                    <p class="text-gray-500 text-sm mb-4 italic">Tema ursinho com nome customizado em Ponto Cruz.</p>
                    <div class="flex justify-between items-center">
                        <span class="text-amber-700 font-bold">Sob Consulta</span>
                        <a href="https://wa.me/5522998665130?text=Quero+uma+toalha+personalizada+para+beb%C3%AA" class="btn-whats text-white p-2 rounded-full px-4 text-xs font-bold">ENCOMENDAR</a>
                    </div>
                </div>
            </div>

            <div class="card-produto bg-white rounded-2xl overflow-hidden shadow-lg">
                <img src="https://i.postimg.cc/85zY8F9y/toalhas-de-banho-e-rosto.jpg" class="w-full h-80 object-cover transition-transform duration-500">
                <div class="p-6">
                    <h4 class="font-bold text-xl mb-2">Conjunto de Banho Floral</h4>
                    <p class="text-gray-500 text-sm mb-4 italic">Kit coordenado com barrado em crochê amarelo.</p>
                    <div class="flex justify-between items-center">
                        <span class="text-amber-700 font-bold">Sob Consulta</span>
                        <a href="https://wa.me/5522998665130" class="btn-whats text-white p-2 rounded-full px-4 text-xs font-bold">CONSULTAR</a>
                    </div>
                </div>
            </div>

            <script>
                for(let i=4; i<=30; i++) {
                    document.write(`
                    <div class="card-produto bg-white rounded-2xl overflow-hidden shadow-lg border-2 border-dashed border-gray-200 opacity-60">
                        <div class="w-full h-80 bg-gray-100 flex items-center justify-center text-gray-400">
                            <i class="fas fa-camera fa-3x"></i>
                        </div>
                        <div class="p-6">
                            <h4 class="font-bold text-xl mb-2 text-gray-300">Nova Criação ${i}</h4>
                            <p class="text-gray-400 text-sm mb-4 italic">Disponível em breve para encomenda.</p>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-300 font-bold">Sob Consulta</span>
                                <a href="https://wa.me/5522998665130" class="bg-gray-200 text-gray-400 p-2 rounded-full px-4 text-xs font-bold cursor-not-allowed">AGUARDAR</a>
                            </div>
                        </div>
                    </div>
                    `);
                }
            </script>

        </div>
    </section>

    <footer class="bg-gray-900 text-white py-20 px-6">
        <div class="container mx-auto grid md:grid-cols-3 gap-12 text-center md:text-left">
            <div>
                <h3 class="text-2xl font-bold text-amber-500 mb-4 italic">Monzato Ateliê</h3>
                <p class="text-gray-400">Artesanato de luxo, feito com a alma de Italva. Entregamos carinho em cada fio.</p>
            </div>
            <div>
                <h4 class="font-bold mb-4">Contato Local</h4>
                <p class="text-gray-400 italic">Italva - Rio de Janeiro</p>
                <p class="text-amber-500 font-bold mt-2">55 22 99866-5130</p>
            </div>
            <div>
                <h4 class="font-bold mb-4">Siga-nos</h4>
                <div class="flex justify-center md:justify-start space-x-4">
                    <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-amber-600 transition"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-amber-600 transition"><i class="fab fa-facebook"></i></a>
                </div>
            </div>
        </div>
        <div class="border-t border-gray-800 mt-16 pt-8 text-center text-gray-500 text-sm">
            © 2026 Monzato Ateliê de Bordados. Orgulhosamente criado em Italva-RJ.
        </div>
    </footer>

</body>
</html>
