# Install

Requires ruby >=2.1

```
gem install bundler
```

```
bundle install
```

### Usage

```
./adsearch --filter='(&(objectclass=user)(samAccountName=*bob*))'

./adsearch --user=bob

./adsearch --group='Domain Admins'
```
