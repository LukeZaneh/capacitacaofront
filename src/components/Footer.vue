<template>
    <footer id="footer" v-show="true">
        <div class="principal">
            <h1>Contato</h1>
            <div class="contato">
                <div>
                    <h3>Telefone</h3>
                    <p>(35) 3829-5188</p>
                </div>
                <div>
                    <h3>Email</h3>
                    <p>contato@compjunior.com.br</p>
                </div>
            </div>
            <div class="localizacao">
                <h3>Localização</h3>
                <div class="textoLocalizacao">
                    <p>Departamento de Ciência da Computação - Av. Central UFLA</p>
                    <p>Aquenta Sol, Lavras - MG</p>
                    <p>37200-000</p>
                </div>
            </div>
            <div class="mapa">
                <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14876.399981353969!2d-44.97853!3d-21.227883!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9ffdf160fd0109%3A0xa973c43f2963f4!2sComp%20J%C3%BAnior!5e0!3m2!1spt-BR!2sbr!4v1684933353764!5m2!1spt-BR!2sbr" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
        </div>
        <b-form class="formulario">
                <b-form-group
                    id="input-group-0"
                    label=""
                    label-for="input-0"
                >
                <b-form-input
                    id="input-0"
                    type="nome"
                    placeholder="Nome"
                    required
                    ></b-form-input>
                 </b-form-group>
                <br>
                <b-form-group
                    id="input-group-1"
                    label=""
                    label-for="input-1"
                >
                <b-form-input
                    id="input-1"
                    type="email"
                    placeholder="Email"
                    required
                    ></b-form-input>
                 </b-form-group>
                <br>
                <b-form-group
                    id="input-group-2"
                    label=""
                    label-for="input-2"
                >
                <b-form-input
                    id="input-2"
                    type="telefone"
                    placeholder="Telefone"
                    required
                    ></b-form-input>
                 </b-form-group>
                <br>
                <b-form-group
                    id="input-group-3"
                    label=""
                    label-for="input-3"
                >
                <b-form-input 
                    id="input-3"
                    type="mensagem"
                    placeholder="Mensagem"
                    required
                    ></b-form-input>
                 </b-form-group>
                 <br>
                 <div class="botao">
                    <b-button>Enviar email</b-button>
                 </div>
        </b-form>
    </footer>
</template>

<script>
/* eslint-disable */
export default {
    name: "Footer",
};
</script>

<style scoped>
.principal {
    margin-top: 5px;
    margin-left: 30px;
    width: 50%;
}
#footer {
    height: 550px;
    background-color: gray;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.mapa {
    width: 487px;
    height: 246px;
}
.mapa iframe {
    width: 487px;
    height: 246px;
    top: 2px;
    left: -546px;
    right: 30px;
}
.contato {
    width: 50%;
    display: flex;
    justify-content: start;
    gap: 50px;
    margin-top: 15px;
}
.textoLocalizacao {
    line-height: 0.15cm;
}
.formulario {
    margin-right: 200px;
    margin-top: 200px;
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    margin-bottom: 40px;
}
</style>