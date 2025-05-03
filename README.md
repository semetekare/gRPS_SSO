# gRPS_SSO

used:
- cleanenv 
- protoc

### Слои

- Transport
  Обработка запросов (gRPC Server)
- Service
  [x] Auth (+jwt)
  [ ] Permissions
  [ ] User Info
- Data
  SQL, Postgre и тд.