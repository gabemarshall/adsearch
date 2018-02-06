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

Ldapsearch output conversion to JSON code is heavily borrowed from  https://gist.github.com/bortels/c9931998b5921d696584406ec6ebf6fc
