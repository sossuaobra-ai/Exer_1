# Primeiro Exercicio
import streamlit as st

# Configuração da página para um visual mais elegante
st.set_page_config(
    page_title="Calculadora Vibe Coding",
    page_icon="🧮",
    layout="centered"
)

# 1. Título principal com ícone amigável
st.title("🧮 Minha Calculadora Interativa")
st.write("Bem-vindo ao seu primeiro aplicativo web em Python com Streamlit!")

# Criando colunas para organizar a interface de forma limpa
col1, col2 = st.columns(2)

# 2. Dois campos de entrada numérica com valores padrão 0.0
with col1:
    num1 = st.number_input("Digite o primeiro número:", value=0.0)

with col2:
    num2 = st.number_input("Digite o segundo número:", value=0.0)

# 3. Componente de seleção para escolher a operação
operacao = st.selectbox(
    "Escolha a operação desejada:",
    ("Soma (+)", "Subtração (-)", "Multiplicação (*)", "Divisão (/)")
)

st.markdown("---")

# 4. Botão de ação com o texto "Calcular"
if st.button("Calcular", type="primary", use_container_width=True):
    # Lógica dos cálculos com tratamento de erros
    if operacao == "Soma (+)":
        resultado = num1 + num2
        simbolo = "+"
    elif operacao == "Subtração (-)":
        resultado = num1 - num2
        simbolo = "-"
    elif operacao == "Multiplicação (*)":
        resultado = num1 * num2
        simbolo = "*"
    elif operacao == "Divisão (/)":
        # 5. Tratamento específico para divisão por zero
        if num2 == 0.0:
            resultado = None
            st.error("🚨 Opa! Não é possível realizar uma divisão por zero. Tente outro número.")
        else:
            resultado = num1 / num2
            simbolo = "/"

    # Se o cálculo for válido, mostre o resultado em grande destaque
    if resultado is not None:
        st.success("Cálculo realizado com sucesso!")
        st.metric(
            label=f"Resultado de: {num1} {simbolo} {num2}",
            value=f"{resultado:.4f}".rstrip('0').rstrip('.') if isinstance(resultado, float) else resultado
        )
