## JavaScript_assigment
##Code
```javascript
const NFTs = [];

function createNFT(_carBrand, _carModel, _carYear, _carColor) {
    const NFT = {
        carBrand: _carBrand,
        carModel: _carModel,
        carYear: _carYear,
        carColor: _carColor,
    };
    NFTs.push(NFT);
}

function displayNFTs() {
    for (let i = 0; i < NFTs.length; i++) {
        console.log("\nID: " + (i + 1));
        console.log("car Brand: " + NFTs[i].carBrand);
        console.log("car Model: " + NFTs[i].carModel);
        console.log("car Year: " + NFTs[i].carYear);
        console.log("car Color: " + NFTs[i].carColor);
    }
}

function getTotalSupply() {
    return NFTs.length;
}

createNFT("Toyata", "Fortuner", "2015", "Black");
createNFT("Mercedes-Benz Maybach", "S-Class", "2022", "Blue");
createNFT("Tesla", "3", "2023", "Red");

displayNFTs();

console.log("\nTotal number of NFTs minted: " + getTotalSupply());
```

##Author

<h3>Created by : <p>Aman Kumar</p></h3>


##License
<p>This project is licensed under the MIT License.</p>
