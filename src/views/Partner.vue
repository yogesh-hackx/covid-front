<template>
  <div class="partner page">
    <h1>Partner With Us</h1>
    <p class="secondary-text">
        We are looking for public and private organizations to partner with, in order to help people access healthcase related information and services. Please get in touch with us at <a href="mailto:contact@covidfyi.in">contact@covidfyi.in</a> to learn more about any of the following (or more ways) to partner.
    </p>
    <div class = "card-group">
        <div class="card">
            <div class="card-head">Product Integrations</div>
            <div class="card-body">
                Have a product that needs pre-verified data or other consolidated information? Looking for a thriving well-established platform to integrate your creation for the people? Need a quick chat to ideate and build quick solutions? We are the perfect choice for you!
            </div>
        </div>
        <div class="card">
            <div class="card-head">Feature Us</div>
            <div class="card-body">
                You came here only because you saw and liked what we did. Help us form new connections and reach more people, by mentioning us in the press media and your social network. Stop people from wasting precious time searching for crucial information by pointing us to everyone you know!
            </div>
        </div>
        <div class="card">
            <div class="card-head">Sponsor Us</div>
            <div class="card-body">
                Impressed by what we can do with zero funding? To survive, sustain and reach a broader audience we need to incur the costs of hosting and developing the platform. We look forward to growing our platform with your backing!
            </div>
        </div>
    </div>
  </div>
  
</template>

<script>

export default {
  name: "partner",
  methods: {
     
  },
  created(){
     window.scrollTo(0,0);
  }
};
</script>

<style scoped>
.partner{
    padding: 80px 50px 80px 50px;
    text-align: left;
    background: var(--dark-background-color);
}
h1 {
    font-size: 28px;
    color: var(--primary-color);
}
h3{
    font-size: 20px;
    color: var(--dark-text-color);
}

.secondary-text{
    font-size: 22px;
    color: var(--light-text-color);
}
a{
    text-decoration: none;
    color: var(--primary-color);
}

.card-group{
    display: flex;
    flex-direction: row;
    margin-top: 10px;
    flex-wrap: wrap;
}
.card-head{
    padding:10px;
    font-size:24px;
    font-weight: bold;
    background-color: var(--primary-color);
    color: var(--light-text-color);
}
.card-body{
    padding:10px;
    font-size: 20px;
    color: var(--light-text-color);
}
.card{
    margin:20px;
    text-align: center;
    flex: 1;
}
.card:first-child{
    margin-left:0;
}
.card:last-child{
    margin-right:0;
}

@media screen and (max-width:800px){
    .card-group{
        flex-direction: column;
    }
    .card{
    
    text-align: left;
    margin-left:0;
    margin-right:0;
}
}

@media screen and (max-width:600px){
    .partner{
    padding: 40px 25px 40px 25px;
    text-align: left;
    background: var(--dark-background-color);
}
h1 {
    font-size: 24px;
    color: var(--primary-color);
}
h3{
    font-size: 16px;
    color: var(--dark-text-color);
}

.secondary-text{
    font-size: 18px;
    color: var(--light-text-color);
}

.card-group{
    flex-direction: column;
    margin-top: 10px;
}

.card-head{
    padding:6px;
    font-size:20px;
    font-weight: bold;
    background-color: var(--primary-color);
    color: var(--light-text-color);
}
.card-body{
    padding:6px;
    font-size: 16px;
    color: var(--light-text-color);
}
.card{
    margin:16px;
    text-align: left;
    margin-left:0;
    margin-right:0;
}
}
</style>