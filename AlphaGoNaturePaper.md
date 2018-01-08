# Mastering the game of Go with deep neural networks and tree search
# 使用深度神经网络和树搜索来精通围棋

>The game of Go has long been viewed as the most challenging of classic games
>for artificial intelligence owing to its enormous search space and the difficulty
>of evaluating board positions and moves. 
>
>长期以来，围棋被认为是对于人工智能最有挑战的经典游戏。这归功于围棋的巨大的搜索空间
>和估算棋盘局势和落子的难度。

>Here we introduce a new approach to computer Go that uses ‘value networks’
>to evaluate board positions and ‘policy networks’ to select moves.
>
>在这里，我们介绍一个新方法来计算围棋。这个方法使用‘值网络’来估算棋盘的局势，使用
>‘策略网络’来选择落子。

>These deep neural networks are trained by a novel combination of supervised learning
>from human expert games, and reinforcement learning from games of self-play.
>Without any lookahead search, the neural networks play Go at the level of stateof-
>the-art Monte Carlo tree search programs that simulate thousands of random games of
>self-play.
>
>训练这些深度神经网络使用了新颖的组合。一部分是使用人类专业棋局进行监督学习，
>另一部分使用深度神经网络的自我对弈进行强化学习。

>We also introduce a new search algorithm that combines Monte Carlo simulation with
>value and policy networks. Using this search algorithm, our program AlphaGo achieved
>a 99.8% winning rate against other Go programs, and defeated the human European Go
>champion by 5 games to 0. 
>
>我们也介绍了一个新的搜索算法。这个算法使用值网络和策略网络组合出蒙特卡洛模拟。
>使用这个搜索算法，我们的程序AlphaGo在面对其他围棋程序时，获得了99.8%的胜率，
>并且以5比0击败了人类的欧洲围棋冠军。

>This is the first time that a computer program has defeated a human professional player
>in the full-sized game of Go, a feat previously thought to be at least a decade away.

>这是第一次，在全尺寸的围棋比赛中，计算机程序击败了一位人类的专业棋手。
>在最近10年的研究中，这是一次壮举。
