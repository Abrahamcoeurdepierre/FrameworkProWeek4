[
    {
      "id": 1,
      "nama": "dfd",
      "harga": 500000,
      "gambar":"https://id-media.apjonlinecdn.com/catalog/product/cache/b3b166914d87ce343d4dc5ec5117b502/2/1/21u62pa.png",
      "stok": 5 
    },
    {
        "id": 2,
        "nama": "dfd",
        "harga": 50045413241000,
        "gambar":"https://id-media.apjonlinecdn.com/catalog/product/cache/b3b166914d87ce343d4dc5ec5117b502/2/1/21u62pa.png",
        "stok": 5 
    },
    {
        "id": 3,
        "nama": "dfd",
        "harga": 500000,
        "gambar":"https://id-media.apjonlinecdn.com/catalog/product/cache/b3b166914d87ce343d4dc5ec5117b502/2/1/21u62pa.png",
        "stok": 5 
    }
]




 {
                       Data.map(artikel => {
                            return <Item    key = {artikel.id}
                                            linkGambar={artikel.gambar}
                                            itemName = {artikel.nama}
                                            itemPrice = {artikel.harga}
                                    />
                        })
                    }
