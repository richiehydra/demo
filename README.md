docker build -f Dockerfile.dev -t react-app:latest .

docker run -d -it --rm -p 3000:3000 --name todo-app react-app:latest

check ur localhost:3000 (container react-app running fine)