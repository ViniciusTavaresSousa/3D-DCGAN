# 3D-DCGAN

Este projeto implementa uma Rede Adversarial Generativa Convolucional Tridimensional (3D DCGAN) para gerar modelos 3D a partir de dados de voxels. Utilizando o conjunto de dados Princeton ModelNet, especificamente modelos de aviões, os dados foram normalizados e padronizados antes do treinamento.

Descrição do Projeto:

A 3D DCGAN é uma arquitetura de rede neural que combina geradores e discriminadores para criar e avaliar modelos 3D. O gerador cria novos voxels enquanto o discriminador tenta distinguir entre dados reais e gerados, melhorando a qualidade das gerações ao longo do treinamento.
Base de Dados

Utilizei o conjunto de dados Princeton ModelNet, focando nos modelos de aviões. Os dados foram carregados e organizados em um formato de voxel, permitindo a geração de modelos 3D.

Estrutura do Projeto:

Gerador: Cria modelos 3D a partir de vetores de ruído.
Discriminador: Avalia a autenticidade dos modelos gerados.
Treinamento: Implementa a lógica de treinamento e salva os modelos gerados.

Referências:

Princeton ModelNet:[ ModelNet](https://modelnet.cs.princeton.edu/)

3D GAN Reference: [3D GAN MIT](http://3dgan.csail.mit.edu/)
