```prisma
model Usuario {
  id    String @id @default(uuid())
  email String @unique
  nome  String
}
```
