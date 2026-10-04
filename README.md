# VidaPlus SGHSS — protótipo front-end

Versão funcional mínima do Sistema de Gestão Hospitalar e de Serviços de Saúde, desenvolvida para a rota de **Front-end** do Projeto Multidisciplinar de ADS.

## Como executar

Na pasta do projeto, inicie o servidor local:

```bash
npm start
```

Depois acesse `http://localhost:4173`.

## Acessos de demonstração

| Perfil | E-mail | Senha |
|---|---|---|
| Paciente | paciente@vidaplus.com | 123456 |
| Profissional | medico@vidaplus.com | 123456 |
| Administrador | admin@vidaplus.com | 123456 |

## Funcionalidades práticas

- Autenticação simulada e controle de navegação por perfil;
- dashboards específicos para paciente, profissional e administrador;
- cadastro e busca de pacientes, com validações e consentimento LGPD;
- agenda semanal e criação de agendamentos;
- prontuário eletrônico e evolução clínica;
- sala simulada de telemedicina;
- gestão de profissionais e indicadores administrativos;
- persistência local dos cadastros e agendamentos;
- layout responsivo, navegação por teclado e regiões acessíveis;
- escape de entradas apresentadas em HTML e testes unitários das regras.

## Testes

```bash
npm test
```

Os dados são fictícios e usados exclusivamente para fins acadêmicos.
