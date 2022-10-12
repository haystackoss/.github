## Skip tests unaffected by code change, save time 👋
```bash
# Install
wget https://nabaz.jfrog.io/artifactory/nabaz-debian-local/pool/stable/nabaz-0.0-amd64.deb -O nabaz.deb
sudo dpkg -i ./nabaz.deb

# Run
cd test-project
nabaz test --cmdline "pytest -v" .
```
