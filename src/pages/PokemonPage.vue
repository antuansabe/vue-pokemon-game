<template>
<h1>¿Quien es este pokemon?</h1>
    <PokemonPicture :pokemonId="8" :showPokemon="true" />
    <PokemonOptions/>
</template>

<script>
import PokemonPicture from '@/components/PokemonPicture'
import PokemonOptions from '@/components/PokemonOptions'
import getPokemonOptions from '@/helpers/getPokemonOptions'



export default {
    components: { PokemonPicture,PokemonOptions }
}
</script>

