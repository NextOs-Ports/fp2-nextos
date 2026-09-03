# EVIDÊNCIA INVALIDADA — 2026-09-02 (auditoria externa)

Os arquivos desta pasta (candidate-lock.json, gptk-event-evidence-*.jsonl, owner-remap,
admissão C6) foram produzidos com o ELF `0755f8ce…` estimulado pelo pad virtual de bancada
DENTRO do port. Provam os sinks internos, não o software de input no hardware-alvo, e o
lock derivado deles alimentou o ZIP `6b8737ae…`, também invalidado.

Preservados como histórico; nenhum deles vale como `input_proof`. A prova válida é
`ON_DEVICE_AUTOMATED_INPUT_PROOF` (nxinput 0.10.2: clones uinput device-faithful no
aparelho real, roteiro gerado pelo nxgenerator 0.3.16, lock pelo nxrelease 0.3.26).
