# sha
git clone https://github.com/DevAlice/AmazingPythonProject.git
cd AmazingPythonProject
echo "def greet(name):" > main.py
echo "    return f'Hello, {name}!'" >> main.py
echo "" >> main.py
echo "print(greet('World'))" >> main.py
git add main.py
git commit -m "Add main script with greeting function"
git push origin main
