# sample-r2

## Install Wrangler
```
$ yarn global add wrangler
```

## Authenticate Wrangler
```
$ wrangler login
```

## Create bucket
```
$ wrangler r2 bucket create sample-bucket
$ wrangler r2 bucket create sample-bucket-preview
```

```
$ wrangler r2 bucket list
```

## Development
```
$ yarn install
$ yarn start
```

## Deployment
```
$ wrangler publish
```
