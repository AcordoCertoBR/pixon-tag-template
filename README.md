# pixon-tag-template

## Implementação
### Passo 1 – Acessar a interface do Google Tag Manager (GTM)


### Passo 2 - Criar uma Tag para o Pixel da Consumidor Positivo
- Selecionar o item `Tags` no menu à esquerda
- Clique em `New` para criar uma nova Tag
- Renomear a tag para o nome mais conveniente e clicar na caneta para editar a tag

### Passo 3 - Selecionar o Modelo (Pixon CP)
- Inserir o Nome do evento de conversão e Nome do parceiro
- Inserir o Acionador (Initialization - All Pages)

```
// Nomes dos eventos para ser utilizados no campo de nome do evento
conversionTrack:pageView
conversionTrack:pageViewStorage
conversionTrack:proposalStarted
conversionTrack:proposalContinued
conversionTrack:proposalCompleted
conversionTrack:preApproved
conversionTrack:approved
conversionTrack:linkClicked
conversionTrack:signedContract
conversionTrack:rejected
conversionTrack:BilletGenerated
conversionTrack:DealClosed
conversionTrack:OfferVisualized
conversionTrack:DebtFound
conversionTrack:SignInCompleted
```

* Repetir o processo para cada nova tag que for inserir no GTM
