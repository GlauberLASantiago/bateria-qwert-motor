Este código implementa um motor de bateria MIDI baseado na Web Audio API, permitindo disparar sons de percussão através do teclado do computador (mapeamento QWERTY). Cada tecla é associada a um "pitch" MIDI e a um sample específico, simulando um kit de bateria.

A lógica central está encapsulada na classe DrumEngine, que gerencia carregamento de samples, reprodução de sons, dinâmica (velocity) e comportamentos musicais como choke (ex: hi-hat).

Para reutilização em outras aplicações:
- Use playByPitch(pitch) para integrar com controladores MIDI
- Use playByCode(code) para teclado
- Customize o KEY_MAP para novos layouts

Este motor pode ser adaptado para drum machines, sequencers, pads virtuais e interfaces de performance.

Baseado no projeto WebAudioFont de Sergey Surikov (https://github.com/surikov/webaudiofont)

Desenvolvido por prof. Glauber Santiago - UFSCar
