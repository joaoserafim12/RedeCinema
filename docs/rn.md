### Regras de Negocio 

RN01 - Verificação de Exclusão. Um filme não pode ser excluído se estiver vinculado a qualquer sessão futura ou histórico de público.

RN02 - Capacidade Estática. A capacidade de público de uma sala só pode ser alterada se não houver sessões ativas agendadas para ela.

RN03 - Conflito de Horário. Uma sala não pode ter sessões sobrepostas. Deve-se somar a duração do filme + 20 min de intervalo entre sessões.

RN04 - Limite de Ocupação. O sistema deve bloquear registros de público que excedam a capacidade total da sala definida no RF02.

RN05 - Visibilidade Temporal. A consulta só deve exibir sessões cujo horário de início seja superior ao horário atual do sistema.
