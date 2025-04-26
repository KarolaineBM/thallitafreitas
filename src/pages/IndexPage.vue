<template>
  <q-page class="q-pa-md">
    <!-- LOGO -->
    <div class="row justify-center">
      <q-img style="max-width: 400px" src="~/assets/logo-bl.png"></q-img>
    </div>

    <!-- TOOLBAR -->
    <div class="row justify-center">
      <div class="col-md-8 col-xs-8">
        <q-toolbar
          class="bg-primary text-white q-pa-md justify-center"
          style="max-width: 90vw; border-radius: 10px"
        >
          <q-btn flat label="Sobre" class="q-mx-sm text-subtitle1" @click="irPara('sobre')" />
          <q-btn flat label="Agenda" class="q-mx-sm text-subtitle1" @click="irPara('agenda')" />
          <q-btn flat label="Dúvidas" class="q-mx-sm text-subtitle1" @click="irPara('duvidas')" />
          <q-btn flat label="Contatos" class="q-mx-sm text-subtitle1" @click="irPara('contatos')" />
        </q-toolbar>
      </div>
    </div>

    <!-- SOBRE 1 -->
    <div class="row q-mt-xl justify-center q-gutter-sm movimento-L">
      <div class="col-md-4 col-xs-4 self-center">
        <span class="text-subtitle1"
          >Olá! Sou Thallita Ferri Freitas, psicóloga formada em 2024, com um olhar atento e
          acolhedor para o bem-estar emocional. Realizo atendimentos online para todas as regiões do
          Brasil, atendendo pessoas de todas as idades, desde crianças e adolescentes até adultos e
          idosos.
        </span>
      </div>
      <div class="col-md-2 col-xs-2">
        <q-img style="max-width: 250px" src="~/assets/img-teste.png"></q-img>
      </div>
    </div>

    <!-- SOBRE 2 -->
    <div class="row q-mt-lg justify-center q-gutter-sm movimento-R">
      <div class="col-md-2 col-xs-2">
        <q-img style="max-width: 250px" src="~/assets/img-teste.png"></q-img>
      </div>
      <div class="col-md-4 col-xs-4 self-center">
        <span class="text-subtitle1"
          >Durante minha trajetória, tive a oportunidade de trabalhar como Acompanhante Terapêutico
          Escolar (AT) por um ano, auxiliando no desenvolvimento emocional de crianças. Também atuei
          na área de quimioterapia no Hospital da Mulher, proporcionando suporte psicológico, e
          trabalhei no CADEVI com atendimentos clínicos.
        </span>
      </div>
    </div>

    <!-- SOBRE 3 -->
    <div class="row q-mt-lg justify-center">
      <div class="col-md-6 col-xs-6">
        <span class="text-bold text-subtitle1"
          >Estou aqui para ajudar você a superar desafios e promover o equilíbrio mental em qualquer
          fase da vida. Vamos juntos encontrar caminhos para uma vida mais saudável e feliz.</span
        >
      </div>
    </div>

    <!-- FITA / FAIXA -->
    <div class="negative-margins q-mt-xl">
      <div class="faixa-degrade q-pa-xl">
        <div class="row justify-center items-center">
          <div class="col-md-3 col-xs-3">
            <span class="text-h5 text-bold">Agende sua consulta online</span>
          </div>
          <div class="col-md-2 col-xs-2">
            <q-btn
              class="text-h5 text-bold"
              label="Agendar"
              color="secondary"
              style="border-radius: 10px"
            />
          </div>
        </div>
      </div>
    </div>

    <!-- DÚVIDAS 1 -->
    <div class="row q-mt-xl">
      <div class="col-md col-xs text-center">
        <span class="text-h4 text-bold text-primary">Dúvidas</span>
      </div>
    </div>

    <!-- DÚVIDAS 2 -->
    <div class="row justify-center">
      <div class="col-md-8 col-xs-12">
        <div class="row justify-center q-mt-lg movimento-R">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="Quanto tempo dura cada sessão?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    A terapia online tem em média a duração de 50 minutos contados a partir do
                    horário agendado, assim, importante a pontualidade para usufruir todo tempo da
                    sessão.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>

        <div class="row justify-center q-mt-md movimento-L">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="Quanto tempo de terapia é necessário?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    Não é possível nem permitido, de acordo com o Código de Ética do Psicólogo, que
                    a profissional faça qualquer tipo de estimativa de tempo do tratamento, bem como
                    prometer ou garantir resultados.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>

        <div class="row justify-center q-mt-md movimento-R">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="Quais as modalidades de pagamento?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    Através de transferência bancária, depósito bancário, pix ou depósito por boleto
                    a solicitar. O pagamento é realizado por sessão e o valor da terapia acompanha o
                    mercado, a formação do profissional e a tabela de sugestão do Conselho de
                    Psicologia.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>

        <div class="row justify-center q-mt-md movimento-L">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="Eu quero fazer sessões eventuais com um psicólogo, posso?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    Você pode marcar seu horário e realizar uma consulta de orientação psicológica,
                    essa sessão é benéfica também, mas não trata as causas dos conflitos. Apenas
                    ajuda a pessoa visualizar uma situação específica por outros ângulos e tomar
                    decisões mais próximas de sua realidade atual.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>

        <div class="row justify-center q-mt-md movimento-R">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="O que é preciso para realizar as sessões de terapia on-line?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    Para realizar a terapia online, é preciso ter 18 anos ou mais, dispor de um
                    computador ou celular com câmera e se possível utilizar fones de ouvido durante
                    a sessão. É recomendável que se organize em um local privativo, que se sinta
                    confortável e seguro para falar.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>

        <div class="row justify-center q-mt-md movimento-L">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="Qual aplicativo é utilizado para realizar a sessão on-line?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    Google Meet, aplicativo criptografado, mantendo a segurança de dados e sigilo.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>

        <div class="row justify-center q-mt-md movimento-R">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="Irei morar fora do Brasil, posso fazer terapia on-line com psicólogo para me preparar?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    Sim, muitas pessoas procuram ajuda terapêutica para se sentirem mais confiantes
                    frente a este novo desafio. Enfrentar uma mudança de país não é simples, mas
                    pode ser bem mais tranquila se você trabalhar suas inseguranças e expectativas.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>

        <div class="row justify-center q-mt-md movimento-L">
          <div class="col-md-8 col-xs-12 text-white">
            <q-list bordered class="rounded-borders bg-primary q-pa-md" style="border-radius: 50px">
              <q-expansion-item
                expand-separator
                header-class="text-h6"
                label="Para quem é indicado passar no psicólogo?"
              >
                <q-card class="text-secondary" style="border-radius: 50px">
                  <q-card-section class="text-center">
                    Um psicólogo é indicado a todas as pessoas que têm alguma insatisfação em
                    qualquer âmbito da vida, como profissional, pessoal, amoroso e/ou financeiro,
                    podendo ser adultos, adolescentes e casais. O acompanhamento com esse
                    profissional trará mais qualidade de vida e poderá solucionar pendências
                    emocionais.
                  </q-card-section>
                </q-card>
              </q-expansion-item>
            </q-list>
          </div>
        </div>
      </div>
    </div>

    <!-- CONTATOS 1 -->
    <div class="row q-mt-xl">
      <div class="col-md col-xs text-center">
        <span class="text-h4 text-bold text-primary">Contatos</span>
      </div>
    </div>

    <!-- CONTATOS 2 -->
    <div class="row q-mt-lg justify-center text-center">
      <dsiv class="col-md-3 col-xs-3"
        ><span class="text-subtitle1"
          ><strong class="text-primary">Email:</strong> thallita.ffreitas@gmail.com</span
        ></dsiv
      >
      <dsiv class="col-md-3 col-xs-3"
        ><span class="text-subtitle1"
          ><strong class="text-primary">Whatsapp:</strong> (11) 99152-1803</span
        ></dsiv
      >
    </div>
  </q-page>
</template>

<script setup>
//import { ref } from "vue";

const irPara = (destino) => {
  console.log('Navegar para:', destino)
  // Aqui você pode depois usar o Vue Router para redirecionar
  // Exemplo: this.$router.push({ name: destino })
}
</script>

<style scoped>
.negative-margins {
  margin-left: -16px;
  margin-right: -16px;
}

.faixa-degrade {
  background: linear-gradient(to bottom, white, var(--q-primary));
  width: 100%;
}

/* MOVIMENTAÇÕES R and L */
@keyframes slideInRight {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}
.movimento-R {
  animation: slideInRight 2s ease-out;
}
@keyframes slideInLeft {
  0% {
    transform: translateX(-100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}
.movimento-L {
  animation: slideInLeft 2s ease-out;
}

/* CAROSSEL */
@media (max-width: 600px) {
  .q-carousel {
    height: auto; /* Garante que o carrossel se ajuste em telas pequenas */
  }
}
.q-carousel {
  background-color: #333; /* Fundo escuro */
}
.q-carousel .q-carousel__control {
  color: #000000; /* Deixa os botões brancos */
}
.carousel-text-container {
  max-width: 100%; /* Garante que o texto não ultrapasse o slide */
  text-align: center; /* Alinha o texto ao centro */
}
.q-carousel {
  height: 600px; /* Define a altura do carrossel */
}

/* ASPAS - PAUTAS */
.quote {
  position: relative;
  font-size: 1.2em;
  line-height: 1.5;
}
.quote::before {
  content: '“';
  font-size: 3em; /* Tamanho das aspas */
  color: #000000; /* Cor das aspas */
  position: absolute;
  top: -20px; /* Ajuste da posição vertical */
  left: -30px; /* Ajuste da posição horizontal */
}
.quote::after {
  content: '”';
  font-size: 3em; /* Tamanho das aspas */
  color: #000000;
  /* color: #5e7364; Cor das aspas */
  position: absolute;
  bottom: -50px; /* Ajuste da posição vertical */
  right: -30px; /* Ajuste da posição horizontal */
}

/* OUTROS */
.line-secondary {
  border: none;
  border-top: 2px solid #e2c2c4; /* Cor 'secondary' do Quasar */
  margin: 0;
}
</style>
