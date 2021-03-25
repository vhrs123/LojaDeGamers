package com.gegames.crudgames.repository;

import java.util.List;

import org.springframework.data.jpa.repository.JpaRepository;

import com.gegames.crudgames.model.Produto;

public interface ProdutoRepository extends JpaRepository<Produto, Long>{
	
	public List<Produto> findAllByTituloContainingIgnoreCase (String titulo); 
	
}
