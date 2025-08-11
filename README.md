# inicializa repo local
git init
git branch -M main
git add .
git commit -m "Publicando portfolio"

# adicionar remote (use a URL do repo que criou no GitHub)
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git

# enviar para o GitHub
git push -u origin main
