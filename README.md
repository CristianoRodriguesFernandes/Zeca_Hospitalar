<?php

class Paciente
{
    // Atributos privados
    private $nome;
    private $rg;
    private $cpf;
    private $endereco;
    private $profissao;

    // Construtor (opcional, caso queira definir os dados ao criar o objeto)
    public function __construct($nome = "", $rg = "", $cpf = "", $endereco = "", $profissao = "")
    {
        $this->nome = $nome;
        $this->rg = $rg;
        $this->cpf = $cpf;
        $this->endereco = $endereco;
        $this->profissao = $profissao;
    }

    // Getters e Setters

    public function getNome()
    {
        return $this->nome;
    }

    public function setNome($nome)
    {
        $this->nome = $nome;
    }

    public function getRg()
    {
        return $this->rg;
    }

    public function setRg($rg)
    {
        $this->rg = $rg;
    }

    public function getCpf()
    {
        return $this->cpf;
    }

    public function setCpf($cpf)
    {
        $this->cpf = $cpf;
    }

    public function getEndereco()
    {
        return $this->endereco;
    }

    public function setEndereco($endereco)
    {
        $this->endereco = $endereco;
    }

    public function getProfissao()
    {
        return $this->profissao;
    }

    public function setProfissao($profissao)
    {
        $this->profissao = $profissao;
    }
}

?>
