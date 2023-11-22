# Esercizio
## Descrizione:
Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!"
## Svolgimento:
1. Cancellare il file .vue nella cartella components e creare il file Title
    - nel file title in script aggiungere un "export default"
    - in template creare un elemento <h2> che ha come testo "la mia prima.."
2. Aprire il file App.vue e:
    - cancellare tutti gli elementi in script, template e style
    - in script importare TitleVue e aggiungere in "export default" il components Title (creato in precedenza)
    - in template aggiungere un:
        - <h1> contenente un testo 
        - aggiungere <Title /> (contenente <h2>)
3. Visualizzare la pagina inserendo nel teminale il comando "npm run dev"