<script>
    import { Deta } from 'deta';
    const deta = Deta("d05z8eyefuv_ggSwyguLjbYLoHxohtXhM59SFouthi7U");
    const db = deta.Base('hero');

    let name = ""
    getArticles()

    async function getArticles() {
        const data = await db.get('123')
        name = data.text
        console.log(data);
        //return data
    }
    function addArticle() {
        let value =  {
            key: '2',
            text: 'Two'
        }
        db.put(value)
    }
    


</script>

<h1>Admin Panel</h1>
<h2>{name}</h2>

<button on:click={addArticle}> addArticle </button>

<style>
    :global(header) {
        display: none !important;
    }
</style>