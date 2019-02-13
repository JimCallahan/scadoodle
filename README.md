# Scadoodle

### Creating 

    npm install express-generator -g
    express --no-view scadoodle

    cd scadoodle
    
    git init
    git add .
    git commit -m "hello world"
    
    
### Initializing

```
cat > .gitignore <<EOF
> package.json
> package-lock.json
> node_modules/
> EOF
```

    git add .gitignore README.md
    git commit -m "initialized node"
    
    
### Running

    DEBUG=scadoodle:* npm start
