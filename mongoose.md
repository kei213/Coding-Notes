# Create Doc
```
Model.create({name, password, email})
```
# Find one by passing parameter
```
Model.findOne({email:req.body.email})
```
# Find by Id
```
Model.findById(id)
```

# Find all and Sort
Model.find({}).sort({createdAt: -1})

# Delete one
```
Model.findOneAndDelete({_id: id})
```

# Update one
```
Model.findOneAndUpdate({_id: id}, {...req.body})
