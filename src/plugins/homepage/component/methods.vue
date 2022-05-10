<script>
    export default{
        data(){
            return{
                //veci ktore zoberem z backendu
                name:'',
                job:'',
                skillsInJob:'',
                money:'',
                city:'',
                //veci ktore vytvorim tu
                card:[
                    {cardID:0},
                    {cardID:1},
                    {cardID:2},
                    {cardID:3},
                    {cardID:4},
                    {cardID:5},
                ],
                cardName:[
                    {names:"Impostor"},
                    {names:"Crewmate1"},
                    {names:"Crewmate2"},
                    {names:"Crewmate3"},
                    {names:"Crewmate4"},
                    {names:"Crewmate5"},
                ],
            }
        },
<<<<<<< HEAD
            methods:{
                addCard(cardID){
                    this.card.push({
                    cardID:cardID+1,
                    })
            },
        },
=======
        methods:{
        addCard(cardID){
            this.card.push({
            cardID:cardID+1,
            })
        }
        } 
>>>>>>> 775385d358eb151b7aba8cbf0b79c07fd6e9837d
    }
    
</script>