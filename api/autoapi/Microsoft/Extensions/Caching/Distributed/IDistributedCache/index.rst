

IDistributedCache Interface
===========================





Namespace
    :dn:ns:`Microsoft.Extensions.Caching.Distributed`
Assemblies
    * Microsoft.Extensions.Caching.Abstractions

----

.. contents::
   :local:









Syntax
------

.. code-block:: csharp

    public interface IDistributedCache








.. dn:interface:: Microsoft.Extensions.Caching.Distributed.IDistributedCache
    :hidden:

.. dn:interface:: Microsoft.Extensions.Caching.Distributed.IDistributedCache

Methods
-------

.. dn:interface:: Microsoft.Extensions.Caching.Distributed.IDistributedCache
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.Get(System.String)
    
        
    
        
        :type key: System.String
        :rtype: System.Byte<System.Byte>[]
    
        
        .. code-block:: csharp
    
            byte[] Get(string key)
    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.GetAsync(System.String)
    
        
    
        
        :type key: System.String
        :rtype: System.Threading.Tasks.Task<System.Threading.Tasks.Task`1>{System.Byte<System.Byte>[]}
    
        
        .. code-block:: csharp
    
            Task<byte[]> GetAsync(string key)
    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.Refresh(System.String)
    
        
    
        
        :type key: System.String
    
        
        .. code-block:: csharp
    
            void Refresh(string key)
    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.RefreshAsync(System.String)
    
        
    
        
        :type key: System.String
        :rtype: System.Threading.Tasks.Task
    
        
        .. code-block:: csharp
    
            Task RefreshAsync(string key)
    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.Remove(System.String)
    
        
    
        
        :type key: System.String
    
        
        .. code-block:: csharp
    
            void Remove(string key)
    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.RemoveAsync(System.String)
    
        
    
        
        :type key: System.String
        :rtype: System.Threading.Tasks.Task
    
        
        .. code-block:: csharp
    
            Task RemoveAsync(string key)
    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.Set(System.String, System.Byte[], Microsoft.Extensions.Caching.Distributed.DistributedCacheEntryOptions)
    
        
    
        
        :type key: System.String
    
        
        :type value: System.Byte<System.Byte>[]
    
        
        :type options: Microsoft.Extensions.Caching.Distributed.DistributedCacheEntryOptions
    
        
        .. code-block:: csharp
    
            void Set(string key, byte[] value, DistributedCacheEntryOptions options)
    
    .. dn:method:: Microsoft.Extensions.Caching.Distributed.IDistributedCache.SetAsync(System.String, System.Byte[], Microsoft.Extensions.Caching.Distributed.DistributedCacheEntryOptions)
    
        
    
        
        :type key: System.String
    
        
        :type value: System.Byte<System.Byte>[]
    
        
        :type options: Microsoft.Extensions.Caching.Distributed.DistributedCacheEntryOptions
        :rtype: System.Threading.Tasks.Task
    
        
        .. code-block:: csharp
    
            Task SetAsync(string key, byte[] value, DistributedCacheEntryOptions options)
    

