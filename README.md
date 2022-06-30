# Friends-API
Usage example 

  async function fetchdata (){



    let url = await fetch('https://my-friends-api.herokuapp.com/friends/1')
    // 1 indicates the id number , you can type 2 as well as 3 also
    let data = await url.json();
    console.log(data);
    sont.innerHTML = `<h1>${data.name}</h1>`;


    }
