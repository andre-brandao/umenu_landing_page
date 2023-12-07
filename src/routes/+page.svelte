<script>
  // Images in the static/cardapios folder
  let imgs = [
    "cardapios/card1.png",
    "cardapios/card2.png",
    "cardapios/card3.png",
    "cardapios/card4.png",
    "cardapios/card5.png",
    "cardapios/card6.png",
    "cardapios/card7.png",
    "cardapios/card8.png",
  ];
</script>

<div class="container h-full mx-auto flex flex-col justify-center items-center p-2">
  <div>
    <h2 class="h2">Revitalize Seu Negócio com o Cardápio Digital</h2>

    <p>
      Desfrute da praticidade de levar seu cardápio para qualquer lugar, sem a necessidade de impressões, e da flexibilidade de atualizá-lo instantaneamente. Ao se conectar conosco, criaremos não apenas um cardápio personalizado para o seu restaurante, mas também revolucionaremos a maneira como você gerencia pedidos.
    </p>

    <p>
      Automatize pedidos, agilize atendimento e proporcione uma experiência única. Modernize seu negócio com nosso serviço de cardápio digital, elevando a satisfação dos clientes a um novo patamar.
    </p>

    <p>
      Desfrute da praticidade de enviar pedidos diretamente para a cozinha, eliminando intermediários e garantindo um fluxo de trabalho mais eficiente.
    </p>
  </div>

  <h3 class="h3">
    Veja Exemplos de Cardápios Digitais
  </h3>
</div>

<div class="snap-x scroll-px-4 snap-mandatory scroll-smooth flex gap-4 overflow-x-auto px-4 py-5">
  {#each imgs as img_src, i}
    <div class="snap-center shrink-0 card w-72 md:w-80 text-center">
      <img class="rounded-lg object-cover" src={"" + img_src} alt="" />
    </div>
  {/each}
</div>

<div class="container h-full mx-auto flex flex-col justify-center items-center p-2">
  <h4 class='h4'>Personalize Seu Caminho para o Sucesso</h4>
  <p>
    Faça parte da revolução digital. Personalize seu cardápio, crie uma experiência única para seus clientes e simplifique operações. Estamos prontos para transformar seu negócio - assine hoje e eleve sua gastronomia a novos patamares.
  </p>

	<img src="pedidos/pedido.png" alt="Pedidos em Tempo Real">

  <h4 class='h4'>Facilidade no Pagamento, Sucesso Garantido</h4>
  <p>
    Desfrute da integração de pagamentos simplificada. Assine agora e garanta o sucesso do seu negócio com um cardápio digital que oferece mais do que você imagina.
  </p>

	<img src="pedidos/ultimospedidos.png" alt="Últimos Pedidos em Tempo Real">

	<h2 class="h2">Os Últimos Pedidos Direto na Cozinha</h2>

	<p>
    Mantenha-se atualizado com os pedidos em tempo real, otimizando a comunicação e agilizando o processo na cozinha.
  </p>

	<h2 class="h2">
		Controle Seu Sucesso com o Sistema Integrado de Estoque
	</h2>

	<p>
		Vá além da gestão de pedidos. Nosso cardápio digital apresenta um sistema de estoque integrado, monitorando gastos e otimizando o controle de inventário. Mantenha-se informado sobre a disponibilidade de produtos, evite desperdícios e tome decisões mais estratégicas para o crescimento sustentável do seu negócio.
	</p>

	<p>
		Não perca a oportunidade de personalizar seu cardápio de acordo com a identidade da sua marca. Adicione produtos, fotos, descrições e altere sempre que desejar. Imagine a facilidade de integração de pagamentos simplificada, oferecendo uma experiência completa e conveniente para seus clientes.
	</p>

	<img src="estoque/estoque.png" alt="Controle de Estoque Integrado">

</div>
