# Coverage commands

## To show coverage in terminal

```bash
go test ./... --cover
```

## To generate a coverage report

```bash
go test ./... -coverprofile=coverage.out
```

## to show coverage report in a browser
```bash
go tool cover -html=coverage.out
```