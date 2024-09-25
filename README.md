## JavaScript_assigment

## Code

```javascript
let nftCollection = [];

function createNFT(name, semester, result, year) {
    const nft = {
        name: name,
        semester: semester,
        result: result,
        year: year
    };
    nftCollection.push(nft);
}

function displayNFTs() {
    nftCollection.forEach((nft, index) => {
        console.log(`NFT ${index + 1}`);
        console.log(`Name: ${nft.name}`);
        console.log(`Semester: ${nft.semester}`);
        console.log(`Result: ${nft.result}`);
        console.log(`Year: ${nft.year}`);
        console.log("----------------------");
    });
}

function getTotalSupply() {
    return nftCollection.length;
}

createNFT("Nitish", "2", "Pass", "2022");
createNFT("Niish kumar", "3", "Fail", "2023");

displayNFTs();
console.log("Total supply: " + getTotalSupply());
```

## Author

<h3>Created by : <p>Aman Kumar</p></h3>


## License
<p>This project is licensed under the MIT License.</p>
