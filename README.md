Hello World 👋

Ok, no problem If you don't know me. Nice to meet you.

#!/usr/bin/python3
# -*- Hello World 👋 -*-

class Me:
    
    def __init__(self):
        
        self.nick_name = "Anderson_de_Sousa_Brito"
        self.name = "Anderson"
        self.role = "Programmer"
        self.language_spoken = ["pt_BR", "en_US"]
        self.location = "Paulinia,São Paulo - Brazil"

        self.knowledge_base = [
            "Python"
            "MySQL"
            "PHP"
            "Database",
            "Security",   
        ]   
        self.knowledge_base.insert(0, "Geek")
        
    def sayHi(self):
        print(
            """Hello my friend, thanks for dropping by!
            Sou um profissional com experiência em análise química adquirida ao trabalhar em um laboratório de analises de combustível. 
            Nesse período, desenvolvi habilidades em análise de densidade de diesel, álcool e gasolina, ponto de fulgor, teor de água no Karl Fisher, 
            destilação de gasolina e diesel, teor alcoólico, pH e condutividade elétrica, viscosidade e confecção de laudos de qualidade.
            No entanto, sempre tive interesse pela área de programação e decidi investir nessa carreira. Atualmente, estou me aprimorando nas habilidades de programação, com foco em Python e Banco de Dados MySQL. 
            Tenho realizado cursos online e escolas profissionalizantes. Meu objetivo é encontrar uma oportunidade entusiasmante para aplicar meus conhecimentos na área de programação, 
            visando contribuir de forma efetiva em projetos que envolvam o desenvolvimento e a análise de sistemas utilizando essas tecnologias. 
            Sou uma pessoa comprometida e proativa, sempre buscando evoluir e aprofundar meu conhecimento nesse campo em constante evolução. Acredito na importância do 
            aprendizado contínuo e estou sempre aberto a novos desafios e oportunidades de crescimento."""
        )
    def sayHi(self):
        print(
           """Hello, my friend, thanks for dropping by!
            I am a professional with experience in chemical analysis acquired while working in a fuel analysis laboratory.
            During this time, I developed skills in analyzing the density of diesel, alcohol, and gasoline, flash point, water content using Karl Fisher method, distillation of gasoline and diesel, alcohol content, 
            pH and electrical conductivity, viscosity, and preparation of quality reports.However, I have always been interested in the programming field and decided to invest in this career. 
            Currently, I am enhancing my programming skills, with a focus on Python and MySQL Database. I have been taking online courses and attending professional schools to further my knowledge. 
            My objective is to find an exciting opportunity to apply my expertise in the programming field, aiming to make effective contributions to projects involving 
            the development and analysis of systems using these technologie. I am a committed and proactive individual, always seeking to evolve and deepen my knowledge in this ever-evolving field. 
            I believe in the importance of continuous learning and I am always open to new challenges and growth opportunities."""
        )

        print("Thanks for dropping by, hope you find some of my work interesting.")
        
me = Me()
me.sayHi()
