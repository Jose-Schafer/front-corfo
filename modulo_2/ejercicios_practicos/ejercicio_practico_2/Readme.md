# Instalar dependencias
> nvm use 18.14
> pnpm install


# Compilar main.css
```sh
pnpm sass styles/main.scss css/main.css
```

# Servir html usando python
```sh
python -m http.server 8000
```

# Tunnel para ver en otros dispositivos
```sh
cloudflared tunnel --url http://localhost:8000
```

