Explicação do Código: Gerando dados sintéticos:

Idade: distribuída em três categorias (jovem, meia-idade, idoso). IMC: valores 0 (normal) ou 1 (sobrepeso). Pressão Arterial: valores 0 (normal) ou 1 (alta). Nível de Glicose: valores 0 (normal) ou 1 (alta). Diagnóstico de Diabetes: variável alvo. A probabilidade de diabetes aumenta com o IMC, pressão alta ou glicose alta. Construindo e treinando o modelo:

A estrutura da rede é a mesma que definimos anteriormente. Usamos a técnica de Máxima Verossimilhança para aprender os parâmetros a partir dos dados gerados. Inferência:

Fazemos uma consulta ao modelo para prever a probabilidade de diabetes em um paciente com características específicas: idade avançada, sobrepeso e pressão alta. Saída Esperada: O modelo retornará as probabilidades de o paciente ter ou não diabetes com base nas variáveis fornecidas como evidência.
