## Modelo Conceitual – Oficina Mecânica

### Entidades Principais

**Cliente**
- id_cliente
- nome
- telefone
- endereço

**Veículo**
- id_veiculo
- placa
- modelo
- ano
- id_cliente

**Mecânico**
- id_mecanico
- codigo
- nome
- endereço
- especialidade

**Equipe**
- id_equipe
- nome

**Ordem de Serviço (OS)**
- id_os
- numero
- data_emissao
- data_conclusao
- status
- valor_total
- id_veiculo
- id_equipe

**Serviço**
- id_servico
- descricao
- valor_mao_obra

**Peça**
- id_peca
- descricao
- valor_unitario
