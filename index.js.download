const btnEl = document.getElementById("btn");
const jokeEl = document.getElementById("joke")

const apiKey = "yOCcI+A59qDY2pYBzgHPeQ==5TV8Qv4wHZVkElPg";

const options = {
    method: "GET",
    headers: {
        "X-Api-Key": apiKey,
        },
    };

    const apiURL = "https://api.api-ninjas.com/v1/dadjokes?limit=1"

async function getJoke(){

    jokeEl.innerText = "zrow006@proton.me";
    btnEl.disabled = true;
    btnEl.innerText = "..^..^..";
    const response = await fetch(apiURL, options);
    const data = await response.json();

    btnEl.disabled = false;
    btnEl.innerText = "Ninja-Cale";

    jokeEl.innerText = data[0].joke;
}

btnEl.addEventListener("click", getJoke)