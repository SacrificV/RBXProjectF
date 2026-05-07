# RBXProjectF
LuaU OOP
Data abstraction - :GetCost() , :FarmTick() and etc.
Encapsulation - self.
Template func - Rune.new(name, config)
STL - Player:GetPlayers()
X-Factor - lookID, task.spawn, task.wait
Exception Handling - onPlayerAdded, assert(), warn()
Inheritance - BaseRune (parent class ) CoinRune and ScoreRune both inherit from it via setmetatable({}, {__index = BaseRune})
Polymorphism - Both CoinRune and ScoreRune override :GetCost() — when rune:GetCost() is called
