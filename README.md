ChatBox Offensive


class ChatBot:
    def __init__(self, nome):
        self.nome = nome
        self.saudacoes = ['oi', 'olá', 'como vai', 'eai', 'oiii', 'oii', 'hai','hi','hey','olaa','opa','opaa','opaaa']
        self.negacoes = ['não foi isso que pedi', 'não é isso', 'errado']
        self.sair = ['sair', 'n', 'no']

    def responder(self, mensagem):
        mensagem = mensagem.lower()
        if any(saudacao in mensagem for saudacao in self.saudacoes):
            return f'Que oi oque cara, vai dar tua bunda, fdp, manda logo o que tu quer, caralho'
        elif 'tudo bom' in mensagem or 'como vai' in mensagem or 'como você está' in mensagem:
            return f'tudo bom o caralho, filho da puta, nao sou teu amigo'
        elif 'dia bonito' in mensagem or 'como está o dia' in mensagem or 'dia maravilhoso' in mensagem or 'ta bom pra ir para a praia ne' in mensagem or 'ta bom pra ir pra praia ne' in mensagem:
            return f'tenho cara de maju coutinho caralho?'
        elif 'o que você acha' in mensagem and 'hoje' in mensagem:
            return f'tenho cara de willian bonner, caralho?'
        elif 'eu amo você' in mensagem or 'eu adoro você' in mensagem:
            return f'da a tua bunda que passa'
        elif 'grosso' in mensagem or 'babaca' in mensagem:
            return f'porque eu quero, e grosso tu vai ver o que é, filho da puta'
        elif 'seu amigo' in mensagem:
            return f'fodasse, ta carente pega um hamster, corno manso'
        elif 'dieta' in mensagem or 'emagrecer' in mensagem:
            return f'\n1. quer emagrecer, fecha a boca filho da puta. \n2. Quer engordar? Come ate virar Thais Carla.'
        elif 'treino' in mensagem or 'academia' in mensagem:
            return f'so cresce se usar bomba filho, adianta querer malhar n.'
        elif 'rotina' in mensagem:
            return f'Acorda, come e dorme. corno manso'
        elif 'programação' in mensagem or 'estudo' in mensagem:
            return f'Claro,ja que voce nao tem dedo, imundo do krlh, aqui esta alguns recursos para estudar programação: \n1. Livros: "Aprenda Python do jeito difícil", "Estrutura e interpretação de programas de computador". \n2. Cursos online: Codecademy, Coursera, Udemy. \n3. Prática de codificação: HackerRank, LeetCode. \nLembre-se, a prática constante é a chave para melhorar suas habilidades de programação.'
        elif any(negacao in mensagem for negacao in self.negacoes):
            return f'Desculpe por não atender às suas expectativas. Por favor, seja mais específico para que eu possa ajudar melhor.'
        elif 'time' in mensagem or 'futebol' in mensagem:
            return f'tenho cara de galvao bueno pra saber disso? vai procurar emprego vagabundo'
        elif 'churn' in mensagem or 'cancelamento' in mensagem or 'desligamento' in mensagem:
            return f'Claro, aqui estão alguns métodos para resolver um cliente churnado ou um cliente que está lhe enchendo o saco: \n1. VIOLENCIA ( resolve de maneira controlada); \n2. TIRO (resolve de maneira bem rapida); \n3. Desligar a chamada na cara dele, mas voce vai sair como mal educada ou fingir que a internet está caindo e desligar a chamada. \n4. ( tem um outro metood também que é aumentar a fatura dele em 2x e depois dizer que foi erro do sistema :D)'
        elif 'policia' in mensagem and 'fugir' in mensagem:
            return f'Claro, aqui estão alguns métodos para fugir da policia ( nao recomendo muito, mas quem nunca, né? ) \n1. primeiro, corra o mais rapido possivel, para um lugar distante, mas antes de correr, desove o corpo em um lugar que ninguem va achar, recomendo nao desovar, e sim jogar em acido sulfurico para dissolver e nao criar resquicios, agora, depois de desovar e correr, va ate o aeroporto e fuja para as bahamas, porque a PRF e o Alexandre de Moraes vao estar atrás de você.)'
        elif 'computador' in mensagem or 'pc' in mensagem:
            return f'Claro, ja que voce um alejado do krlh e nao consegue pesquisar por si só e ven encher a porra do meu saco pra perguntar isso, aqui esta alguns recursos para estudar computadores: \n1. Cursoemvideo; \n2. Udemy; \n3. Videos no Youtube; \n4. Projetos no Github; \n5. Internet aberta'
        elif 'xingar' in mensagem or 'descer a lenha' in mensagem:
            return f'Claro, diz o nome ou o que do arrombado pra nos xingar junto ai meu brother)'
        elif 'sou ruim' in mensagem or 'video game' in mensagem:
            return f'Claro, ta passando raiva em joguinho amigao? Nao ta na hora de uma carteira de trabalho nao? Corno manso, alem de desempregado é ruim no jogo, da alt f4 da vida ai irmao)'
        elif 'namoro' in mensagem or 'relacionamento' in mensagem:
            return f'Irmao, enquanto tu ta mandando aqui isso pra mim, tua mina ta dando, se bem que nem mina tu deve ter, cara fedido, vai tomar banho mlk'
        elif 'trabalho' in mensagem or 'job' in mensagem:
            return f'vai fazer glub glub no teu chefe, vai'
        elif 'viajar' in mensagem or 'outro país' in mensagem:
            return f'tomara que teu avião caia'
        elif 'Brasil' in mensagem:
            return f'KKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKK \n1. O CARA ACHA QUE BRASIL TEM SOLUÇAO \n2. KKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKKkk'
        elif 'Alexandre' in mensagem or 'Alexandre de Moraes' in mensagem or 'xandao' in mensagem or 'xandão' in mesangem:
            return f'meu grande lider, esse ai é um cara respeitoso e de acordo com a lei, um cara íntregro, bondoso, de bem com a lei. (nao me fode, muda de assunto caralho)'
        elif 'Lula' in mensagem or '9 dedos' in mensagem or 'lulinha' in mensagem or 'lulao' in mensagem:
            return f' Nosso presidente, nosso cachaceiro preferido, queria tomar uma pinga com ele, camarada, grande camarada Lula ( quer me fuder mermo ne ?)'
        elif 'economizar' in mensagem or 'juntar dinheiro' in mensagem:
            return f' Na minha opnião, isso ai tem que ser TRINCHEIRA. Tem que ser levado a sério, pois a situação que a banda toca no teu país, nao da pra saber o que vai acontecer amanha nao.'
        elif 'ue' in mensagem:
            return f'UE O CARALGO FILHO DA PUTA'    
        else:
            return f'Fale algo que eu entenda, seu chimpanzé filho da puta.'
    def iniciar(self):
        while True:
            mensagem = input('Você: ')
            if mensagem.lower() == 'sair':
                break
            resposta = self.responder(mensagem)
            print(f'{self.nome}: {resposta}')
# Criação do chatbot
bot = ChatBot('FdpBox')

# Loop do chatbot
bot.iniciar()
