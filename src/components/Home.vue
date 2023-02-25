<template>
<div class="space">
<div id="maindown">
<div id="dropdown">
    <label for="down"></label>
    <select name="down" id="down">
    <option value="Collectables/Photography">Collectables/Photography</option>
    <option value="Photography">Photography</option>
  </select>
</div>

<div id="dropdown">
    <label for="down"></label>
    <select name="down" id="down">
    <option value="Lowest to Highest">Lowest to Highest</option>
    <option value="Highest">Highest</option>
  </select>
</div>

<div id="dropdown">
    <label for="down"></label>
    <select name="down" id="down">
    <option value="All">All</option>
  </select>
</div>

</div>
<div id="search">
<input type="text" id="myInput" placeholder="Search" title="Type in a name">
<button type="button" id="btn4"><i class="fa-sharp fa-solid fa-magnifying-glass"></i></button>
</div>
<table id="example" class="table table-striped" style="width:100%">
    <thead id="hide">
        <tr id="data" class="title">
            <th>Title</th>
            <th>Highest Bidder</th>
            <th>Auction Time</th>
            <th>Highest Bid</th>
            <th>Action</th>
        </tr>
    </thead>
    <tbody id="all">
        <tr>
            <td id="data2" ><div id="maindiv"><img src="https://app.3schools.in/logo.png" height="50" width="50"></div><div id="text">3D Neon Art - Test Item 7</div><div id="text2">By Sanya</div><div><button id="btn3">Art</button></div></td>
            <td id="you2" class="data4"><button id="you">You</button></td>
            <td id="data" class="data4">4d:16h:12m:24s</td>
            <td id="data" class="data4">4.20 SDX <sub>(10.30 USD)</sub></td>
            <td id="data3"><button type="button" id="btn">Place Bid</button><button type="button" id="btn1"><i class="fa-solid fa-share-nodes"></i></button></td>
        </tr>
        <tr >
            <td id="data2" ><div id="maindiv"><img src="https://app.3schools.in/logo.png" height="50" width="50"></div><div id="text">3D Neon Art - Test Item 7</div><div id="text2">By Sanya</div><div><button id="btn3">Art</button></div></td>
            <td id="data" class="data4">Nelly Kutwojk</td>
            <td id="data" class="data4">4d:16h:12m:24s</td>
            <td id="data" class="data4">4.20 SDX <sub>(10.30 USD)</sub></td>
            <td id="data3" class="data4"><button type="button" id="btn">Place Bid</button><button type="button" id="btn1"><i class="fa-solid fa-share-nodes"></i></button></td>
        </tr>
        <tr >
            <td id="data2" ><div id="maindiv"><img src="https://app.3schools.in/logo.png" height="50" width="50"></div><div id="text">3D Neon Art - Test Item 7</div><div id="text2">By Sanya</div><div><button id="btn3">Art</button></div></td>
            <td id="data" class="data4">Peter Grey</td>
            <td id="data" class="data4">4d:16h:12m:24s</td>
            <td id="data" class="data4">4.20 SDX <sub>(10.30 USD)</sub></td>
            <td id="data3" class="data4"><button type="button" id="btn">Place Bid</button><button type="button" id="btn1"><i class="fa-solid fa-share-nodes"></i></button></td>
        </tr>
        <tr>
            <td id="data2" ><div id="maindiv"><img src="https://app.3schools.in/logo.png" height="50" width="50"></div><div id="text">3D Neon Art - Test Item 7</div><div id="text2">By Sanya</div><div><button id="btn3">Art</button></div></td>
            <td id="data" class="data4">Andrew Collects</td>
            <td id="data" class="data4">4d:16h:12m:24s</td>
            <td id="data" class="data4">4.20 SDX <sub>(10.30 USD)</sub></td>
            <td id="data3"><button type="button" id="btn">Place Bid</button><button type="button" id="btn1"><i class="fa-solid fa-share-nodes"></i></button></td>
        </tr>
        <tr>
            <td id="data2" ><div id="maindiv"><img src="https://app.3schools.in/logo.png" height="50" width="50"></div><div id="text">3D Neon Art - Test Item 7</div><div id="text2">By Sanya</div><div><button id="btn3">Art</button></div></td>
            <td id="data" class="data4">FAJ NFT Test</td>
            <td id="data" class="data4">4d:16h:12m:24s</td>
            <td id="data" class="data4">4.20 SDX <sub>(10.30 USD)</sub></td>
            <td id="data3"><button type="button" id="btn">Place Bid</button><button type="button" id="btn1"><i class="fa-solid fa-share-nodes"></i></button></td>
        </tr>
    </tbody>
</table>
</div>
</template>

<script>

</script>

<style scoped>

#maindown{
    display: flex;
    margin: 0px 0px -30px 0px;
}

#down{
    color: aliceblue;
    padding: 0px 15px 0px 15px ;
}
#dropdown{
    border: 1px solid rgb(201, 6, 152);
    margin-right: 1rem;
}
#maindiv{
    float: left;
    margin: 5px 25px 0px 0px;
}
#data2{
    color: white;
}
#data3{
    padding: 20px 0px 0px 0px;
}

#text{
    margin: -5px 0px 1px 0px;

}

#text2{
    font-size: 13px;
    margin: -5px 0px 1px 0px;

}

.title{
    background-color: rgb(29, 38, 59);
}
.space{
    margin: 80px 80px 0px 80px;
}

#btn{
    border: 2px solid rgb(201, 6, 152);
    color: rgb(201, 6, 152);
    padding: 0px 15px 0px 15px;
    margin: 0px 10px 0px 0px;
}

#btn1{
    border: 2px solid rgb(201, 6, 152);
    color: rgb(201, 6, 152);
    padding: 0px 10px 0px 10px;
}
#btn3{
    border: rgb(201, 6, 152);
    color: rgb(255, 255, 255);
    background-color: rgb(201, 6, 152);
    padding: 0px 10px 0px 10px;
    font-size: 13px;
}
#btn4{
    border: 2px solid rgb(201, 6, 152);
    color: rgb(255, 255, 255);
    padding: 0px 10px 0px 10px;
    margin: 0px 10px 0px 0px;
}



#you{
    border: green;
    background-color: green;
    color: aliceblue;
    padding: 0px 10px 0px 10px;
    margin-left: 20px;

}

#you2{
    padding: 20px 0px 0px 0px;
}

#data{
    color: white;
    padding: 20px 0px 0px 0px;
}

#search{
    float: right;
    margin-bottom: 1rem;
}

#myInput{
    border: 2px solid rgb(192, 10, 147);
    margin: 0px 0px 0px 0px;
}

/* --------------------RESPONSIVE------------------- */

@media screen and (max-width: 900px) {
#maindown{
    display: none;
}

#hide{
    display: none;
}

#all{
    margin:0px 0px 0px 0px;
}

#btn{
    margin: 93px 2px 18px -247px;
    padding: 0px 70px 0px 70px;
}
#text{
    margin: -3px -56px 4px 75px;
}

#data{
display: none;
}

#you2{
    display: none;
}

}

</style>
