# MongoIntro




db.blogs.insertOne({
    "createdAt": "2022-01-14T15:07:41.214Z",
	 "title": 'Boxing',
	 "text": "Nulla expedita libero ut accusantium vitae repellat et. Accusantium ipsa expedita ratione harum provident quia totam. Dicta facilis dicta saepe et. Est et delectus veritatis nihil. Magnam dolor iste perspiciatis officia blanditiis possimus.\nTotam alias corrupti doloribus. Nihil laboriosam expedita omnis nihil. Eos delectus nulla sit magni aut quae distinctio deserunt.\nAutem et aliquam quasi nam. Vero enim ullam voluptas ut quidem libero rerum. Nam omnis illo voluptatem non tempore ipsum. Qui nulla fugiat rerum.",
	 "author": "Joe Louis",
	 "categories": ["rerum", "mollitia", "voluptas"],
	 "id": "4a571289-6d5c-4300-9614-53c6e1237d81",
	 "objectId": "27"
    
})


db.bios.findOne(
    { },
    { author: "Joe Louis" }
)
db.bios.findAll(
   {},
            { createdAt: { $gt: new Date('04/01/2022') } }
          
   
)

db.bios.findAll(
   {},
            { objectId: { $gt: 5 } }
          
   
)


