ansible-role-neo4j-graph-algorithms
===================================

[![Build Status](https://travis-ci.org/kevincoakley/ansible-role-neo4j-graph-algorithms.svg?branch=master)](https://travis-ci.org/kevincoakley/ansible-role-neo4j-graph-algorithms)

Install Efficient Graph Algorithms for Neo4j (https://github.com/neo4j-contrib/neo4j-graph-algorithms) . Tested with Neo4j 3.5.4 on CentOS 7 and Ubuntu 18.04. 

Requirements
------------

Neo4j - https://github.com/kevincoakley/ansible-role-neo4j

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------
        
    - name: Test the Neo4J Graph Algorithms role
      hosts: neo4j-graph-algorithms
      become: yes
      become_method: sudo
    
      roles:
        - ansible-role-neo4j
        - ansible-role-neo4j-graph-algorithms
    
      tags:
        - neo4j-graph-algorithms

License
-------

BSD

Author Information
------------------

Kevin Coakley (https://github.com/kevincoakley)
